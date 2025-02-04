---
title: "removeVirtualGuestAccess"
description: "Remove a CloudLayer Computing Instance from a portal user's access list. A user's CloudLayer Computing Instance access list controls which of an account's computing instances a user has access to in the SoftLayer customer portal and API. CloudLayer Computing Instances do not exist in the SoftLayer portal and returns 'not found' exceptions in the API if the user doesn't have access to it. If a user does not has access to the CloudLayer Computing Instance you're attempting remove add then removeVirtualGuestAccess() returns true. 

Users can assign CloudLayer Computing Instance access to their child users, but not to themselves. An account's master has access to all CloudLayer Computing Instances on their customer account and can set instance access for any of the other users on their account. "
date: "2018-02-12"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer"
type: "reference"
layout: "method"
mainService : "SoftLayer_User_Customer"
---

### [REST Example](#removeVirtualGuestAccess-example) <a href="/article/rest/"><i class="fas fa-question"></i></a> {#removeVirtualGuestAccess-example .anchor-link} 
```bash
curl -g -u $SL_USER:$SL_APIKEY -X POST -d '{"parameters": [int]}' \
'https://api.softlayer.com/rest/v3.1/SoftLayer_User_Customer/{SoftLayer_User_CustomerID}/removeVirtualGuestAccess'
```
