---
title: "getSecurityScanRequests"
description: "An account's vulnerability scan requests."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account"
type: "reference"
layout: "method"
mainService : "SoftLayer_Account"
---

### [REST Example](#getSecurityScanRequests-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getSecurityScanRequests-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Account/{SoftLayer_AccountID}/getSecurityScanRequests'
```
