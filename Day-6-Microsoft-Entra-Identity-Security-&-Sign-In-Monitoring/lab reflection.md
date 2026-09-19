# Week 4 – Day 6: Microsoft Entra Sign-In and Audit Logs

## Objective

The goal of this lab was to learn how to review Microsoft Entra sign-in logs and audit logs and understand how they can be used for security monitoring and investigation.

## Lab Environment

* Microsoft Azure
* Microsoft Entra ID
* Azure Lab User
* Azure-Lab-Users
* Azure-Lab-Helpdesk
* Homelab-RG

## Tasks Completed

* Reviewed Microsoft Entra sign-in logs.
* Reviewed recent sign-in activity.
* Examined sign-in information such as location, device, authentication details, and Conditional Access information.
* Reviewed Microsoft Entra audit logs.
* Compared sign-in logs with audit logs.
* Considered how unusual sign-in activity could indicate a security issue.
* Reviewed how MFA and Conditional Access can help protect accounts.
* Learned how logs can support security investigations.

## Sign-In Logs

Sign-in logs provide information about user authentication and sign-in activity.

Information that can be reviewed includes:

* User
* Date and time
* Location
* Device information
* Authentication details
* Application
* Sign-in status
* Conditional Access information

Sign-in logs can help administrators determine who accessed resources, where the sign-in came from, and what device was used.

## Audit Logs

Audit logs provide information about changes and administrative activities within Microsoft Entra.

Examples include:

* User changes
* Group changes
* Role assignments
* Administrative activities
* Other configuration changes

### Sign-In Logs vs Audit Logs

| Sign-In Logs                       | Audit Logs                                          |
| ---------------------------------- | --------------------------------------------------- |
| Show user sign-in activity         | Show changes and administrative activity            |
| Provide authentication information | Provide information about changes made              |
| Help investigate unusual sign-ins  | Help investigate unauthorized or unexpected changes |

## Security Investigation Example

An unfamiliar location or device could indicate that an account may have been compromised.

An administrator could review:

* Date and time
* Location
* Device
* Application
* Authentication details
* Sign-in status
* Conditional Access information

This information can help determine whether the activity was expected or requires further investigation.

## MFA and Conditional Access

MFA provides an additional authentication factor. This means that a stolen password alone may not be enough to access a resource when MFA is required.

Conditional Access can apply additional security requirements or block access when specific conditions are not met.

Sign-in logs allow administrators to review the resulting sign-in activity.

Together:

**MFA → Helps verify the user's identity**

**Conditional Access → Applies access requirements based on conditions**

**Sign-In Monitoring → Helps administrators review and investigate activity**

## What I Learned

I was able to learn more about audit logs and sign-in logs and how they can be used for security purposes. I learned that sign-in logs provide information about user authentication and access activity, while audit logs provide information about changes and administrative activities.

I also learned how administrators can use information such as location, device, authentication details, and sign-in status to investigate unusual activity.

## Challenges

Everything worked fine during today's lab. I did not experience any major problems or errors.

## Screenshots

The following screenshots document the lab:

1. Microsoft Entra Sign-In Logs
2. Sign-In Details
3. Microsoft Entra Audit Logs

## Key Takeaways

* Sign-in logs help monitor user authentication and access activity.
* Audit logs help track changes and administrative activities.
* Unusual locations or devices can require further investigation.
* MFA provides an additional authentication factor.
* Conditional Access can apply security requirements based on conditions.
* Logs provide useful information during security investigations.


