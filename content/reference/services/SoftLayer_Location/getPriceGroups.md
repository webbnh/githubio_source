---
title: "getPriceGroups"
description: "Retrieve a location can be a member of 1 or more Price Groups. This will show which groups to which a location belongs."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Location"
classes:
    - "SoftLayer_Location"
---
# SoftLayer_Location::getPriceGroups
## Overview 
Retrieve a location can be a member of 1 or more Price Groups. This will show which groups to which a location belongs.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_LocationInitParameters
* authenticate

### Optional Headers
* SoftLayer_LocationObjectMask
* SoftLayer_LocationObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Location_Group'>SoftLayer_Location_Group[] </a>