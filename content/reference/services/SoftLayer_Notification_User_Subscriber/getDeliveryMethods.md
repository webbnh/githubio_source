---
title: "getDeliveryMethods"
description: "Retrieve the delivery methods used to send the subscribed notification."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Notification"
classes:
    - "SoftLayer_Notification_User_Subscriber"
---
# SoftLayer_Notification_User_Subscriber::getDeliveryMethods
## Overview 
Retrieve the delivery methods used to send the subscribed notification.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Notification_User_SubscriberInitParameters
* authenticate

### Optional Headers
* SoftLayer_Notification_User_SubscriberObjectMask
* SoftLayer_Notification_User_SubscriberObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Notification_Delivery_Method'>SoftLayer_Notification_Delivery_Method[] </a>