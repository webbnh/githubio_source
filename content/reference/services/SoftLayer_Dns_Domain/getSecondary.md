---
title: "getSecondary"
description: "Retrieve the secondary DNS record that defines this domain as being managed through zone transfers."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Dns"
classes:
    - "SoftLayer_Dns_Domain"
---
# SoftLayer_Dns_Domain::getSecondary
## Overview 
Retrieve the secondary DNS record that defines this domain as being managed through zone transfers.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Dns_DomainInitParameters
* authenticate

### Optional Headers
* SoftLayer_Dns_DomainObjectMask
* SoftLayer_Dns_DomainObjectFilter
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Dns_Secondary'>SoftLayer_Dns_Secondary </a>