---
title: "getEvents"
description: "Retrieve the events which have taken place on a network storage volume."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage"
---
# SoftLayer_Network_Storage::getEvents
## Overview 
Retrieve the events which have taken place on a network storage volume.

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
<a href='/reference/datatypes/SoftLayer_Network_Storage_Event'>SoftLayer_Network_Storage_Event[] </a>