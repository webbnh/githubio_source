---
title: "getParent"
description: "A billing item's parent item. If a billing item has no parent item then this value is null."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Billing"
classes:
    - "SoftLayer_Billing_Item_Virtual_DedicatedHost"
type: "reference"
layout: "method"
mainService : "SoftLayer_Billing_Item_Virtual_DedicatedHost"
---

### [REST Example](#getParent-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getParent-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Billing_Item_Virtual_DedicatedHost/{SoftLayer_Billing_Item_Virtual_DedicatedHostID}/getParent'
```
