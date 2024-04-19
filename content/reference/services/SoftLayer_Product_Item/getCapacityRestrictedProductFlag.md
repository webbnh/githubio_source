---
title: "getCapacityRestrictedProductFlag"
description: "This flag indicates that this product is restricted by a capacity on a related product."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Product"
classes:
    - "SoftLayer_Product_Item"
type: "reference"
layout: "method"
mainService : "SoftLayer_Product_Item"
---

### [REST Example](#getCapacityRestrictedProductFlag-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getCapacityRestrictedProductFlag-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Product_Item/{SoftLayer_Product_ItemID}/getCapacityRestrictedProductFlag'
```