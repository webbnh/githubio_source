---
title: "OrderConsistentPerfFileStorage.php"
description: "OrderConsistentPerfFileStorage.php"
date: "2017-11-23"
classes: 
    - "SoftLayer_SoapClient"
    - "SoftLayer_Container_Product_Order"
    - "SoftLayer_Product_Item_Price"
    - "SoftLayer_Container_Product_Order_Network_Storage_Enterprise"
    - "SoftLayer_Product_Package"
    - "SoftLayer_Product_Order"
    - "SoftLayer_Container_Product_Order_Network_PerformanceStorage_Nfs"
tags:
    - "networkstorage"
---


```php
<?php
/**
 * Order Consistent Performance File Storage
 *
 * This script orders a Consistent Performance File Storage
 *
 * Important manual pages:
 * @see http://sldn.softlayer.com/reference/services/SoftLayer_Product_Order/placeOrder
 * @see http://sldn.softlayer.com/reference/datatypes/SoftLayer_Container_Product_Order
 * @see http://sldn.softlayer.com/reference/datatypes/SoftLayer_Container_Product_Order_Network_PerformanceStorage_Nfs
 *
 * @license <http://sldn.softlayer.com/wiki/index.php/license>
 * @author SoftLayer Technologies, Inc. <sldn@softlayer.com>
 */
require_once dirname(__FILE__) . "/SoftLayer/SoapClient.class.php";

/**
 * Your SoftLayer API username
 * @var string
 */
$username = "set me";

/**
 * Your SoftLayer API key
 * Generate one at: https://control.softlayer.com/account/users
 * @var string
 */
$apiKey = "set me";

/**
 * Declare the location, packageId and quantity for the Endurance that you wish to order
 * @var int $location
 * @var int $packageId
 * @var int $quantity
 */
$location = 449596; // Melbourne 1
$packageId = 222; // The packageID for order Performance
$quantity = 1;

// Create a SoftLayer API client object for "SoftLayer_Product_Order" service
$client = SoftLayer_SoapClient::getClient('SoftLayer_Product_Order', null, $username, $apiKey);

/**
 * Build a skeleton SoftLayer_Product_Item_Price objects. These objects contain
 * much more than ids, but SoftLayer's ordering system only needs the price's id
 * to know what you want to order.
 * To get the list of valid prices for the package
 * use the SoftLayer_Product_Package:getItems method
 */
$prices = array(
40662, // Block Storage (Performance)
63091, // 500 GB Storage Space 
66609 // 500 IOPS 
);

$orderPrices = array();
foreach ($prices as $priceId) {
    $price = new stdClass();
    $price -> id = $priceId;
    $orderPrices[] = $price;
}

// Build a SoftLayer_Container_Product_Order_Network_Storage_Enterprise object containing
// the order you wish to place.
$orderContainer = new stdClass();
$orderContainer -> location = $location;
$orderContainer -> packageId = $packageId;
$orderContainer -> prices = $orderPrices;
$orderContainer -> quantity = $quantity;

// Re-declare the order template as a SOAP variable, so the SoftLayer ordering system knows what type of order you're placing.
$orderTemplate = new SoapVar($orderContainer, SOAP_ENC_OBJECT, 'SoftLayer_Container_Product_Order_Network_PerformanceStorage_Nfs', 'http://api.service.softlayer.com/soap/v3/');

try {
    /**
     * We will use verifyOrder() method to check for errors. Replace this with placeOrder() when you are ready to order.
     * @see http://sldn.softlayer.com/reference/services/SoftLayer_Product_Order/verifyOrder
     */
    $result = $client -> placeOrder($orderTemplate);
    print_r($result);
} catch(Exception $e) {
    echo "Unable to order Consistent Performance File Storage" . $e -> getMessage();
}

```
