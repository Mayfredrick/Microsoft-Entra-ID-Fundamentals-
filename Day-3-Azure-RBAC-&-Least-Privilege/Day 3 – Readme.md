# Week 4 Day 3 – Azure RBAC & Least Privilege

## Objective

The objective of this lab was to understand Azure Role-Based Access Control (RBAC), assign permissions to a security group, verify user access, and understand the importance of least privilege.

## Lab Environment

* Microsoft Azure
* Resource Group: `Homelab-RG`
* Test User: `Azure Lab User`
* Security Group: `Azure-Lab-Helpdesk`
* Azure RBAC Role: `Reader`
* RBAC Scope: `Homelab-RG`

## Tasks Completed

* Reviewed Azure RBAC roles.
* Reviewed the `Homelab-RG` resource group.
* Assigned the Reader role to the `Azure-Lab-Helpdesk` security group.
* Verified the role assignment through Access Control (IAM).
* Used Check Access to review the permissions associated with the test user.
* Reviewed the differences between Reader, Contributor, and Owner.
* Applied the principle of least privilege.
* Tested the Azure Lab User account.

## RBAC Role Assignment

I assigned the **Reader** role to the `Azure-Lab-Helpdesk` security group.

The Reader role allows users to view Azure resources but does not allow them to make changes.

The `Azure Lab User` account was a member of the helpdesk group, allowing the user to receive the permissions assigned to that group.

## Scope

The Reader role was assigned at the **resource group scope**:

`Homelab-RG`

Scope determines the level or area where an Azure RBAC role applies.

## Access Verification

I used **Access Control (IAM)** and **Check Access** to verify the permissions.

The access information showed the role, description, scope, group assignment, and conditions.

I also tested the `Azure Lab User` account.

During testing, I initially could not sign in because I entered the username incorrectly. The correct username was `azlabuser`, but I initially entered `azurelabuser`. After correcting the spelling, I was able to sign in successfully.

## Least Privilege

The principle of least privilege means giving users only the access and permissions they need to perform their responsibilities.

Using the Reader role for a user who only needs to view resources helps prevent unnecessary access and reduces potential security risks.

## Screenshots

The following screenshots were captured during the lab:

* RBAC Reader role assignment
* Azure-Lab-Helpdesk group assignment
* Check Access results
* Azure RBAC role information

## Challenges

I initially had trouble signing in with the Azure Lab User account.

After troubleshooting, I discovered that the username was entered incorrectly. I used `azurelabuser` instead of the correct username, `azlabuser`.

After correcting the username, the account was able to sign in successfully.

## What I Learned

I gained a better understanding of Azure RBAC and how permissions can be assigned to users and security groups.

I learned the difference between the Reader, Contributor, and Owner roles and how scope determines where a role applies.

I also learned how to use Access Control (IAM) and Check Access to verify permissions.

Most importantly, I learned how group-based access and the principle of least privilege can help administrators manage access more efficiently and securely.
