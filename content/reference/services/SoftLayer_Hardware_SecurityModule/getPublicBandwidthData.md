---
title: "getPublicBandwidthData"
description: "Retrieve a graph of a server's public network bandwidth usage over the specified timeframe. If no timeframe is specified... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_SecurityModule"
aliases:
    - "/reference/services/softlayer_hardware_securitymodule/getPublicBandwidthData"
---
# [SoftLayer_Hardware_SecurityModule](/reference/services/SoftLayer_Hardware_SecurityModule)::getPublicBandwidthData

Retrieve a graph of a server's public network usage.


## Overview 
Retrieve a graph of a server's public network bandwidth usage over the specified timeframe. If no timeframe is specified then getPublicBandwidthGraphImage retrieves the last 24 hours of public bandwidth usage. getPublicBandwidthGraphImage returns a PNG image measuring 827 pixels by 293 pixels. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|startTime| integer| The starting point to retrieve bandwidth data from, specified as a [[dateTime|date]].|
|endTime| integer| The end point to retrieve bandwidth data to, specified as a [[dateTime|date]].|


### Required Headers
* authenticate
* SoftLayer_Hardware_SecurityModuleInitParameters

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Metric_Tracking_Object_Data'>SoftLayer_Metric_Tracking_Object_Data[] </a>

### External Links


* [Portable Network Graphics at Wikipedia](http://en.wikipedia.org/wiki/Portable_Network_Graphics)


