# Week 4 Day 3 – Azure RBAC & Least Privilege Reflection

### 1. What is Azure RBAC?

Azure RBAC is a permission control system based on the role assigned to a user, group, or other identity. It controls what actions they can perform on Azure resources.

### 2. Why assign a role to a security group instead of an individual user?

Assigning a role to a security group allows access to be managed for a group of users instead of assigning permissions to each individual user. This can make access easier to manage and help reduce mistakes.

### 3. What does the Reader role allow a user to do?

The Reader role allows a user to view Azure resources but does not allow them to make changes.

### 4. What does the Contributor role allow a user to do?

The Contributor role allows a user to view and manage Azure resources, but the user cannot assign roles to other users.

### 5. What additional ability does the Owner role have compared with Contributor?

The Owner role provides full access to Azure resources, including the ability to manage access and assign roles to other users.

### 6. What does scope mean in Azure RBAC?

Scope is the level or area where an Azure RBAC role is applied. It determines which resources the assigned permissions apply to.

### 7. At what scope did you assign the Reader role?

I assigned the Reader role at the `Homelab-RG` resource group scope.

### 8. What happened when you checked access for Azure Lab User?

When I checked access for the Azure Lab User, Azure showed information about the role, description, scope, group assignment, and conditions.

### 9. Why is Reader a good role for a helpdesk employee who only needs to view resources?

The Reader role is useful because it follows the principle of least privilege. It allows the user to view resources without giving them unnecessary permissions to make changes.

### 10. Why is least privilege important?

Least privilege is important because it gives users access only to the resources and permissions they need. Giving users unnecessary access to other resources can create security concerns.

### 11. What did you learn from today's lab?

I learned how to check access and assign an Azure RBAC role to a user or group. I also gained a better understanding of how roles and scope control access to Azure resources.

### 12. Did you encounter any problems?

I initially had trouble signing in with the Azure Lab User account. After troubleshooting, I discovered that I had entered the username incorrectly. The correct username was `azlabuser`, but I had entered `azurelabuser`. After correcting the spelling, I was able to sign in successfully.
