---
title: "addApiAuthenticationKey"
description: "Create a user's API authentication key, allowing that user access to query the SoftLayer API. addApiAuthenticationKey()... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
aliases:
    - "/reference/services/softlayer_user_customer_openidconnect/addApiAuthenticationKey"
---
# [SoftLayer_User_Customer_OpenIdConnect](/reference/services/SoftLayer_User_Customer_OpenIdConnect)::addApiAuthenticationKey

Create a user's API authentication key.


## Overview 
Create a user's API authentication key, allowing that user access to query the SoftLayer API. addApiAuthenticationKey() returns the users new API key. Each portal user is allowed a maximum of two API keys. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_User_Customer_OpenIdConnectInitParameters

### Optional Headers

### Return Values
string


### associatedMethods

*  [SoftLayer_User_Customer::removeApiAuthenticationKey](/reference/services/SoftLayer_User_Customer/removeApiAuthenticationKey )

