---
title: "getDependentDuplicates"
description: "The network storage volumes configured to be dependent duplicates of a volume."
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_Backup_Evault"
type: "reference"
layout: "method"
mainService : "SoftLayer_Network_Storage_Backup_Evault"
---

### [REST Example](#getDependentDuplicates-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#getDependentDuplicates-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X GET \
'https://api.softlayer.com/rest/v3.1/SoftLayer_Network_Storage_Backup_Evault/{SoftLayer_Network_Storage_Backup_EvaultID}/getDependentDuplicates'
```
