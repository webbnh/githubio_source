---
title: "getUser"
description: "The customer user that initiated a report request."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account_Reports_Request"
type: "reference"
layout: "method"
mainService : "SoftLayer_Account_Reports_Request"
---

### [REST Example](#getUser-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getUser-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Account_Reports_Request/{SoftLayer_Account_Reports_RequestID}/getUser'
```
