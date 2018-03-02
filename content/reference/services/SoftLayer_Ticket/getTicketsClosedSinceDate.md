---
title: "getTicketsClosedSinceDate"
description: "Retrieve all tickets closed since a given date."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Ticket"
classes:
    - "SoftLayer_Ticket"
---
# SoftLayer_Ticket::getTicketsClosedSinceDate
## Overview 
Retrieve all tickets closed since a given date. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|closeDate| dateTime| Retrieve all ticket closed since this date.|


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_TicketObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a>