---
title: "getPopLocationAvailabilityFlag"
description: "This flag indicates if the package may be available in PoP locations in addition to Datacenters."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Product"
classes:
    - "SoftLayer_Product_Package"
type: "reference"
layout: "method"
mainService : "SoftLayer_Product_Package"
---

### [REST Example](#getPopLocationAvailabilityFlag-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getPopLocationAvailabilityFlag-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Product_Package/{SoftLayer_Product_PackageID}/getPopLocationAvailabilityFlag'
```
