---
title: "updateMaintenanceWindow"
description: "In case an upgrade cannot be performed, the maintenance window needs to be updated to a future date."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Product"
classes:
    - "SoftLayer_Product_Upgrade_Request"
---
# SoftLayer_Product_Upgrade_Request::updateMaintenanceWindow
## Overview 
In case an upgrade cannot be performed, the maintenance window needs to be updated to a future date. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|maintenanceStartTime| dateTime| A maintenance window starting time in ISO 8601 format.|
|maintenanceWindowId| integer| |


### Required Headers
* authenticate
* SoftLayer_Product_Upgrade_RequestInitParameters

### Optional Headers

### Return Values
boolean