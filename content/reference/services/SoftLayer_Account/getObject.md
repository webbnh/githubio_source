---
title: "getObject"
description: "getObject retrieves the SoftLayer_Account object whose ID number corresponds to the ID number of the init parameter pass... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account"
---
# SoftLayer_Account::getObject
## Overview 
getObject retrieves the SoftLayer_Account object whose ID number corresponds to the ID number of the init parameter passed to the SoftLayer_Account service. You can only retrieve the account that your portal user is assigned to. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_AccountObjectMask
* SoftLayer_AccountObjectFilter
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Account'>SoftLayer_Account </a>