---
title: "updateForumPassword"
description: "This method is deprecated! SoftLayer Community Forums no longer exist, therefore, this method will return false. In the... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer"
aliases:
    - "/reference/services/softlayer_user_customer/updateForumPassword"
---
# [SoftLayer_User_Customer](/reference/services/SoftLayer_User_Customer)::updateForumPassword

Update a user's forum password


## Overview 
This method is deprecated! SoftLayer Community Forums no longer exist, therefore, this method will return false. In the future, this method will be completely removed. 

Update a user's password on the SoftLayer community forums. As with portal passwords, user forum passwords must match the following restrictions. Forum passwords must... 
* ...be over eight characters long.
* ...be under twenty characters long.
* ...contain at least one uppercase letter
* ...contain at least one lowercase letter
* ...contain at least one number
* ...contain one of the special characters _ - | @ . , ? / ! ~ # $ % ^ & * ( ) { } [ ] \ + =
* ...not match your username
* ...not match your portal password
Finally, users can only update their own password. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|password| string| Your new forum password|


### Required Headers
* authenticate
* SoftLayer_User_CustomerInitParameters

### Optional Headers

### Return Values
void


### associatedMethods

*  [SoftLayer_User_Customer::updatePassword](/reference/services/SoftLayer_User_Customer/updatePassword )

