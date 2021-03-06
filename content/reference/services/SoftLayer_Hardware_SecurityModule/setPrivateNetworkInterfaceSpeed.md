---
title: "setPrivateNetworkInterfaceSpeed"
description: "Sets the private network interface speed to the new speed. Speed values can only be 0 (Disconnect), 10, 100, 1000, and 1... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_SecurityModule"
aliases:
    - "/reference/services/softlayer_hardware_securitymodule/setPrivateNetworkInterfaceSpeed"
---
# [SoftLayer_Hardware_SecurityModule](/reference/services/SoftLayer_Hardware_SecurityModule)::setPrivateNetworkInterfaceSpeed

Updates the private network interface (eth0) speed.


## Overview 
Sets the private network interface speed to the new speed. Speed values can only be 0 (Disconnect), 10, 100, 1000, and 10000. The new speed must be equal to or less than the max speed of the interface. 

It will take less than a minute to update the switch port speed. The server uplink will not be operational again until the server interface speed is updated. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|newSpeed| integer| New speed for private network component|


### Required Headers
* authenticate
* SoftLayer_Hardware_SecurityModuleInitParameters

### Optional Headers

### Return Values
boolean

