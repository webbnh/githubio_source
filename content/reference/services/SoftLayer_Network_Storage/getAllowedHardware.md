---
title: "getAllowedHardware"
description: "Retrieve the SoftLayer_Hardware objects which are allowed access to this storage volume."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage"
---
# SoftLayer_Network_Storage::getAllowedHardware
## Overview 
Retrieve the SoftLayer_Hardware objects which are allowed access to this storage volume.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_StorageInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_StorageObjectMask
* SoftLayer_Network_StorageObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a>