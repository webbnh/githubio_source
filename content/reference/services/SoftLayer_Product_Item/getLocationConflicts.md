---
title: "getLocationConflicts"
description: "An item's location conflicts. For example, Dual Path network functionality cannot be ordered in WDC and as such is a conflict."
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

### [REST Example](#getLocationConflicts-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getLocationConflicts-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Product_Item/{SoftLayer_Product_ItemID}/getLocationConflicts'
```