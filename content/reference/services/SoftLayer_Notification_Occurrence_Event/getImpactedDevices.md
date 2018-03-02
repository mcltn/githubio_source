---
title: "getImpactedDevices"
description: "This method will return a collection of SoftLayer_Notification_Occurrence_Resource objects which is a listing of the cur... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Notification"
classes:
    - "SoftLayer_Notification_Occurrence_Event"
---
# SoftLayer_Notification_Occurrence_Event::getImpactedDevices
## Overview 
This method will return a collection of SoftLayer_Notification_Occurrence_Resource objects which is a listing of the current users' impacted devices that are associated with this event. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Notification_Occurrence_EventInitParameters

### Optional Headers
* SoftLayer_Notification_Occurrence_EventObjectMask
* SoftLayer_ObjectMask
* resultLimit

### Return Values
<a href='/reference/datatypes/SoftLayer_Notification_Occurrence_Resource'>SoftLayer_Notification_Occurrence_Resource[] </a>
