---
title: "getAccount"
description: "The Account whose RWHOIS data was used to SWIP this subnet"
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Subnet_Swip_Transaction"
type: "reference"
layout: "method"
mainService : "SoftLayer_Network_Subnet_Swip_Transaction"
---

### [REST Example](#getAccount-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getAccount-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Network_Subnet_Swip_Transaction/{SoftLayer_Network_Subnet_Swip_TransactionID}/getAccount'
```
