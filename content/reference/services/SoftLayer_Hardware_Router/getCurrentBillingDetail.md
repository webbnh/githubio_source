---
title: "getCurrentBillingDetail"
description: "Get the billing detail for this hardware for the current billing period. This does not include bandwidth usage. "
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_Router"
type: "reference"
layout: "method"
mainService : "SoftLayer_Hardware_Router"
---

### [REST Example](#getCurrentBillingDetail-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getCurrentBillingDetail-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Hardware_Router/{SoftLayer_Hardware_RouterID}/getCurrentBillingDetail'
```
