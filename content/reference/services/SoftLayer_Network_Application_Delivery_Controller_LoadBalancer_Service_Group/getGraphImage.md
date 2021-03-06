---
title: "getGraphImage"
description: "Get the graph image for a load balancer service group based on the supplied graph type and metric.  The only available g... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Application_Delivery_Controller_LoadBalancer_Service_Group"
aliases:
    - "/reference/services/softlayer_network_application_delivery_controller_loadbalancer_service_group/getGraphImage"
---
# [SoftLayer_Network_Application_Delivery_Controller_LoadBalancer_Service_Group](/reference/services/SoftLayer_Network_Application_Delivery_Controller_LoadBalancer_Service_Group)::getGraphImage

Get the connection or status graph image for a load balancer service group.


## Overview 
Get the graph image for a load balancer service group based on the supplied graph type and metric.  The only available graph type currently is: 'connections', and the available metrics are: 'day', 'week' and 'month'. 

This method returns the raw binary image data. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|graphType| string| The graph type can currently only be 'connections'.|
|metric| string| The metric can be 'day', 'week', or 'month'.|


### Required Headers
* authenticate
* SoftLayer_Network_Application_Delivery_Controller_LoadBalancer_Service_GroupInitParameters

### Optional Headers

### Return Values
binary data

