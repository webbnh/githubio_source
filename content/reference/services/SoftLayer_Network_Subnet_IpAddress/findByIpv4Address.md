---
title: "findByIpv4Address"
description: "Search for an IP address record by IPv4 address."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Subnet_IpAddress"
---
# SoftLayer_Network_Subnet_IpAddress::findByIpv4Address
## Overview 
Search for an IP address record by IPv4 address.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|ipAddress| string| The IP address to search for|


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_Network_Subnet_IpAddressObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress </a>