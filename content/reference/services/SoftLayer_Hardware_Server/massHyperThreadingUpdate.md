---
title: "massHyperThreadingUpdate"
description: "You can launch hyper-threading update by selecting from your server list. It will bring your server offline for approximately 60 minutes while the updates are in progress. 

In the event of a hardware failure during this update our datacenter engineers will be notified of the problem automatically. They will then replace any failed components to bring your server back online. They will be in contact with you to ensure that impact on your server is minimal. "
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_Server"
type: "reference"
layout: "method"
mainService : "SoftLayer_Hardware_Server"
---

### [REST Example](#massHyperThreadingUpdate-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#massHyperThreadingUpdate-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X POST -d '{"parameters": [int, boolean]}' \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Hardware_Server/massHyperThreadingUpdate'
```
