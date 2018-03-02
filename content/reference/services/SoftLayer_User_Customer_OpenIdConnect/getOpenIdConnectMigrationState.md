---
title: "getOpenIdConnectMigrationState"
description: "This API returns a SoftLayer_Container_User_Customer_OpenIdConnect_MigrationState object containing the necessary inform... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
---
# SoftLayer_User_Customer_OpenIdConnect::getOpenIdConnectMigrationState
## Overview 
This API returns a SoftLayer_Container_User_Customer_OpenIdConnect_MigrationState object containing the necessary information to determine what migration state the user is in. If the account is not OpenIdConnect authenticated, then an exception is thrown. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_User_Customer_OpenIdConnectInitParameters

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Container_User_Customer_OpenIdConnect_MigrationState'>SoftLayer_Container_User_Customer_OpenIdConnect_MigrationState </a>