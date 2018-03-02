---
title: "getMonitoringAgents"
description: "Retrieve the program (monitoring agent) that gets details of a system or application and reporting of the metric data an... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Monitoring"
classes:
    - "SoftLayer_Monitoring_Robot"
---
# SoftLayer_Monitoring_Robot::getMonitoringAgents
## Overview 
Retrieve the program (monitoring agent) that gets details of a system or application and reporting of the metric data and triggers alarms for predefined events.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Monitoring_RobotInitParameters
* authenticate

### Optional Headers
* SoftLayer_Monitoring_RobotObjectMask
* SoftLayer_Monitoring_RobotObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Monitoring_Agent'>SoftLayer_Monitoring_Agent[] </a>