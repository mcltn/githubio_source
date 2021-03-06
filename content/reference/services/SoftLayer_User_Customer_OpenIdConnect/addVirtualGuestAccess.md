---
title: "addVirtualGuestAccess"
description: "Add a CloudLayer Computing Instance to a portal user's access list. A user's CloudLayer Computing Instance access list c... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
aliases:
    - "/reference/services/softlayer_user_customer_openidconnect/addVirtualGuestAccess"
---
# [SoftLayer_User_Customer_OpenIdConnect](/reference/services/SoftLayer_User_Customer_OpenIdConnect)::addVirtualGuestAccess

Add a CloudLayer Computing Instance to a portal user's access list.


## Overview 
Add a CloudLayer Computing Instance to a portal user's access list. A user's CloudLayer Computing Instance access list controls which of an account's CloudLayer Computing Instance objects a user has access to in the SoftLayer customer portal and API. CloudLayer Computing Instances do not exist in the SoftLayer portal and returns "not found" exceptions in the API if the user doesn't have access to it. If a user already has access to the CloudLayer Computing Instance you're attempting to add then addVirtualGuestAccess() returns true. 

Users can assign CloudLayer Computing Instance access to their child users, but not to themselves. An account's master has access to all CloudLayer Computing Instances on their customer account and can set CloudLayer Computing Instance access for any of the other users on their account. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|virtualGuestId| integer| The identifier of the Virtual Server to add to a user's access list.|


### Required Headers
* authenticate
* SoftLayer_User_Customer_OpenIdConnectInitParameters

### Optional Headers

### Return Values
boolean


### associatedMethods

*  [SoftLayer_User_Customer::addBulkVirtualGuestAccess](/reference/services/SoftLayer_User_Customer/addBulkVirtualGuestAccess )
*  [SoftLayer_User_Customer::removeVirtualGuestAccess](/reference/services/SoftLayer_User_Customer/removeVirtualGuestAccess )
*  [SoftLayer_User_Customer::removeBulkVirtualGuestAccess](/reference/services/SoftLayer_User_Customer/removeBulkVirtualGuestAccess )

