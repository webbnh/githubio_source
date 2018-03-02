---
title: "getHardware"
description: "Retrieve a portal user's accessible hardware. These permissions control which hardware a user has access to in the SoftL... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
---
# SoftLayer_User_Customer_OpenIdConnect::getHardware
## Overview 
Retrieve a portal user's accessible hardware. These permissions control which hardware a user has access to in the SoftLayer customer portal.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_User_Customer_OpenIdConnectInitParameters
* authenticate

### Optional Headers
* SoftLayer_User_Customer_OpenIdConnectObjectMask
* SoftLayer_User_Customer_OpenIdConnectObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a>