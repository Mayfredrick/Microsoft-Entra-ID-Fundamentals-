Week 4 – Day 5: Microsoft Entra Conditional Access

Objective

The goal of this lab was to learn how Microsoft Entra Conditional Access can be used to control access to resources based on specific conditions. I also learned how Conditional Access works together with Multi-Factor Authentication (MFA) and Role-Based Access Control (RBAC).

Lab Environment
Microsoft Azure
Microsoft Entra ID
Azure Lab User
Azure-Lab-Users
Azure-Lab-Helpdesk
Homelab-RG

Tasks Completed
Reviewed Microsoft Entra Conditional Access.
Reviewed the different Conditional Access policy settings.
Reviewed users, target resources, conditions, grant controls, and session controls.
Reviewed how MFA can be used with Conditional Access.
Compared Conditional Access with RBAC.
Reviewed the principle of least privilege.
Investigated why the New Policy option was unavailable.
Verified that my account had the Conditional Access Administrator role.
Tested the Conditional Access page and received a license-related error.
What I Learned

1. Conditional Access

Microsoft Entra Conditional Access allows administrators to control access to resources based on certain conditions.

2. Conditional Access vs MFA

Conditional Access uses specific conditions to determine whether additional access requirements should be applied, while MFA verifies a user's identity using factors such as what you know, what you have, or who you are.

3. If/Then Security

Conditional Access works using an if/then approach. If certain criteria are met, the specified access requirement can be applied. If the requirements are not met, access can be blocked.

4. Unfamiliar Locations or Devices

Requiring MFA when a user signs in from an unfamiliar location or device provides an additional security check. If someone has obtained a user's password, the additional MFA requirement can help prevent unauthorized access.

5. Conditional Access and MFA

Conditional Access can require MFA when certain conditions are met. For example, if a user signs in from an unfamiliar device or location, Conditional Access can require MFA before allowing access.

6. Conditional Access vs RBAC

Conditional Access controls whether a user can access a resource based on certain conditions. RBAC controls what a user is allowed to do after they have access.

7. Least Privilege

Least privilege helps ensure that users receive only the access they need to perform their job. This reduces unnecessary access and helps protect resources.

8. Conditional Access Conditions

Conditions can include information such as the user's location, device, application, sign-in risk, and other sign-in information.

9. When Access Is Blocked

If a Conditional Access policy blocks a user, the user may be prevented from accessing the resource until the required conditions are satisfied.

10. Testing Policies

Administrators should test Conditional Access policies before enforcing them to make sure the policy works as expected and does not accidentally block legitimate users.

11. Report-Only Mode

Report-only mode is useful because administrators can review what would happen if a Conditional Access policy were applied without actually enforcing the policy.

Lab Challenge

I was unable to create and test a Conditional Access policy because my Azure tenant does not have the required Microsoft Entra ID Premium license.

I verified that my account had the Conditional Access Administrator role. The Azure portal returned a 401 error stating that a Microsoft Entra ID Premium license is required to use the feature.

Instead of changing the lab environment or purchasing a license, I reviewed the Conditional Access settings and learned how policies, conditions, MFA, and RBAC work together.

What I Learned Today

Today I learned that Conditional Access can be used to apply additional security requirements based on specific conditions. I also learned how Conditional Access works together with MFA and RBAC.

The most important concept I learned was the difference between the three:

Conditional Access: Determines what access requirements should apply based on conditions.
MFA: Helps verify that the person signing in is really the user.
RBAC: Determines what the user is allowed to do after receiving access.

Although I could not create a policy because of the tenant licensing limitation, I was able to troubleshoot the issue, identify the cause, and continue learning the concepts behind Conditional Access.

Errors / Issues

Issue: Conditional Access policy creation was unavailable.

Error: 401 – You need a Microsoft Entra ID Premium license to use this feature.

Cause: The Azure tenant does not have the required Microsoft Entra ID Premium licensing.

Troubleshooting: Verified the Conditional Access Administrator role and reviewed the Conditional Access configuration.

Result: Documented the licensing limitation and continued the lab through configuration review and conceptual learning.