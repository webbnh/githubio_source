---
title: "getEligibleAlarmSubscibers"
description: "This method returns an array of SoftLayer_User_Customer objects, representing those who are allowed to be used as alarm... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Monitoring"
classes:
    - "SoftLayer_Monitoring_Agent"
---
# SoftLayer_Monitoring_Agent::getEligibleAlarmSubscibers
## Overview 
This method returns an array of SoftLayer_User_Customer objects, representing those who are allowed to be used as alarm subscribers. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Monitoring_AgentInitParameters

### Optional Headers
* SoftLayer_Monitoring_AgentObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer[] </a>