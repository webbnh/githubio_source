---
title: "executeRemoteScript"
description: "Download and run remote script from uri on the hardware."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware"
type: "reference"
layout: "method"
mainService : "SoftLayer_Hardware"
---

### [REST Example](#executeRemoteScript-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#executeRemoteScript-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X POST -d '{"parameters": [string]}' \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Hardware/{SoftLayer_HardwareID}/executeRemoteScript'
```
