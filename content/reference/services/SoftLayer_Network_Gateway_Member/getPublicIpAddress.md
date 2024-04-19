---
title: "getPublicIpAddress"
description: "The public gateway IP address."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Gateway_Member"
type: "reference"
layout: "method"
mainService : "SoftLayer_Network_Gateway_Member"
---

### [REST Example](#getPublicIpAddress-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getPublicIpAddress-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Network_Gateway_Member/{SoftLayer_Network_Gateway_MemberID}/getPublicIpAddress'
```