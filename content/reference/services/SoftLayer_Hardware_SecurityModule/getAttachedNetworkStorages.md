---
title: "getAttachedNetworkStorages"
description: "This method is retrieve a list of SoftLayer_Network_Storage volumes that are authorized access to this SoftLayer_Hardwar... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_SecurityModule"
---
# SoftLayer_Hardware_SecurityModule::getAttachedNetworkStorages
## Overview 
This method is retrieve a list of SoftLayer_Network_Storage volumes that are authorized access to this SoftLayer_Hardware. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|nasType| string| either 'ISCSI', 'NAS', or '*' for both|


### Required Headers
* authenticate
* SoftLayer_Hardware_SecurityModuleInitParameters

### Optional Headers
* SoftLayer_Hardware_SecurityModuleObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a>
