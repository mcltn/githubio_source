---
title: "createFromSubnet"
description: "This method is used to create a new SoftLayer_Network_Storage_Allowed_Host using an existing SoftLayer_Network_Subnet ob... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_Allowed_Host_Hardware"
aliases:
    - "/reference/services/softlayer_network_storage_allowed_host_hardware/createFromSubnet"
---
# [SoftLayer_Network_Storage_Allowed_Host_Hardware](/reference/services/SoftLayer_Network_Storage_Allowed_Host_Hardware)::createFromSubnet

Creates and returns a new SoftLayer_Network_Storage_Allowed_Host.


## Overview 
This method is used to create a new SoftLayer_Network_Storage_Allowed_Host using an existing SoftLayer_Network_Subnet object's id. Allowed_Host objects created for SoftLayer_Network_Subnet objects do not support IQNs. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|subnetId| integer| The ID of the SoftLayer_Network_Subnet object to create a SoftLayer_Network_Storage_Allowed_Host object for.|


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_Network_Storage_Allowed_Host_HardwareObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Storage_Allowed_Host_Hardware'>SoftLayer_Network_Storage_Allowed_Host_Hardware </a>

