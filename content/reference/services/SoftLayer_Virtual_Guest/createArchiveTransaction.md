---
title: "createArchiveTransaction"
description: "Create a transaction to archive a computing instance's block devices"
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Virtual"
classes:
    - "SoftLayer_Virtual_Guest"
---
# SoftLayer_Virtual_Guest::createArchiveTransaction
## Overview 
Create a transaction to archive a computing instance's block devices

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|groupName| string| the group name for the archive|
|blockDevices| <a href='/reference/datatypes/SoftLayer_Virtual_Guest_Block_Device'>SoftLayer_Virtual_Guest_Block_Device[] </a>| The block devices to archive|
|note| string| A long note describing the image template|


### Required Headers
* authenticate
* SoftLayer_Virtual_GuestInitParameters

### Optional Headers
* SoftLayer_Virtual_GuestObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Provisioning_Version1_Transaction'>SoftLayer_Provisioning_Version1_Transaction </a>