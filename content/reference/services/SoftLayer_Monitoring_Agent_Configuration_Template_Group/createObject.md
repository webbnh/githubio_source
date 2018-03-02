---
title: "createObject"
description: "This method creates a SoftLayer_Monitoring_Agent_Configuration_Template_Group using the values provided in the template... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Monitoring"
classes:
    - "SoftLayer_Monitoring_Agent_Configuration_Template_Group"
---
# SoftLayer_Monitoring_Agent_Configuration_Template_Group::createObject
## Overview 
This method creates a SoftLayer_Monitoring_Agent_Configuration_Template_Group using the values provided in the template object. The template objects accountId will be overridden to use the active user's accountId as it shows on their associated SoftLayer_User_Customer object. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|templateObject| <a href='/reference/datatypes/SoftLayer_Monitoring_Agent_Configuration_Template_Group'>SoftLayer_Monitoring_Agent_Configuration_Template_Group </a>| The SoftLayer_Monitoring_Agent_Configuration_Template_Group object that you wish to create.|


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_Monitoring_Agent_Configuration_Template_GroupObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Monitoring_Agent_Configuration_Template_Group'>SoftLayer_Monitoring_Agent_Configuration_Template_Group </a>