---
title: "getWindowsUpdateAvailableUpdates"
description: "Retrieve a list of Windows updates available for a server from the local SoftLayer Windows Server Update Services (WSUS)... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_SecurityModule750"
aliases:
    - "/reference/services/softlayer_hardware_securitymodule750/getWindowsUpdateAvailableUpdates"
---
# [SoftLayer_Hardware_SecurityModule750](/reference/services/SoftLayer_Hardware_SecurityModule750)::getWindowsUpdateAvailableUpdates

Retrieve a list of Windows updates available to a server.


## Overview 
Retrieve a list of Windows updates available for a server from the local SoftLayer Windows Server Update Services (WSUS) server. Windows servers provisioned by SoftLayer are configured to use the local WSUS server via the private network by default. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Hardware_SecurityModule750InitParameters

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Container_Utility_Microsoft_Windows_UpdateServices_UpdateItem'>SoftLayer_Container_Utility_Microsoft_Windows_UpdateServices_UpdateItem[] </a>

### External Links


* [Windows Server Update Services (WSUS) Home](http://technet.microsoft.com/en-us/wsus/default.aspx)

