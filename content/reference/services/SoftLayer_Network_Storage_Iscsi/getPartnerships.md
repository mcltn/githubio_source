---
title: "getPartnerships"
description: "Retrieve the volumes or snapshots partnered with a network storage volume."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_Iscsi"
---
# SoftLayer_Network_Storage_Iscsi::getPartnerships
## Overview 
Retrieve the volumes or snapshots partnered with a network storage volume.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_Storage_IscsiInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_Storage_IscsiObjectMask
* SoftLayer_Network_Storage_IscsiObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Storage_Partnership'>SoftLayer_Network_Storage_Partnership[] </a>
