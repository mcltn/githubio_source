---
title: "getCurrentBillingTotal"
description: "The '''getCurrentBillingTotal''' method retrieves the total bill amount in US Dollars ($) for the current billing period... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware"
aliases:
    - "/reference/services/softlayer_hardware/getCurrentBillingTotal"
---
# [SoftLayer_Hardware](/reference/services/SoftLayer_Hardware)::getCurrentBillingTotal

Get the total billing price for this instance's hourly usage up to this point. This includes total includes all bandwidth charges.


## Overview 
The '''getCurrentBillingTotal''' method retrieves the total bill amount in US Dollars ($) for the current billing period. In addition to the total bill amount, the billing detail also includes all bandwidth used up to the point the method is called on the piece of hardware. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_HardwareInitParameters

### Optional Headers

### Return Values
decimal

