# Identity

## Objective

The goal of this lab is to understand how to configure and manage Microsoft Entra ID (formerly Azure Active Directory) to provide authentication, authorisation, and secure access control in Azure environments.

### Skills Learned

You will learn how to manage Microsoft Entra ID by creating and securing users, groups, and roles while exploring authentication methods and hybrid identity with Azure AD Connect. You will strengthen access security using Multi-Factor Authentication, Conditional Access, and Self-Service Password Reset, along with governance through Privileged Identity Management and access reviews. Finally, you will gain experience enabling external collaboration with B2B identities and entitlement management workflows.

### Tools Used

This lab utilises Microsoft Entra ID, Azure AD Connect for directory synchronisation, Privileged Identity Management, Conditional Access, Multi-Factor Authentication, Self-Service Password Reset, Access Reviews, Entitlement Management, and, optionally, Active Directory Domain Services hosted on Azure virtual machines.

## Steps

Every screenshot should include text that explains its content.
You will begin by exploring the basics of identity and familiarizing yourself with the objects in Entra ID such as users, groups, devices, and applications. Next, you will create new users and groups, assigning them as needed to test access and collaboration scenarios. If you are working with a hybrid environment, you will install and configure Azure AD Connect to synchronise your on-premises directory with Entra ID.

Once identity is set up, you will configure authentication by testing password hash synchronisation, pass-through authentication, and federation options. You will also work with modern authentication to understand how it differs from legacy methods. After that, you will manage administrative access by assigning built-in or custom roles and using Privileged Identity Management to enable just-in-time elevation of privileges.

With identities and roles in place, you will secure access by enforcing Multi-Factor Authentication and creating Conditional Access policies that define when and how MFA is required. You will then enable Self-Service Password Reset, configure Access Reviews to ensure least-privilege access, and set up Entitlement Management packages to automate access requests and approvals.

Finally, you will experiment with external collaboration by inviting a guest user to your tenant and applying policies and entitlement workflows to them. You will finish the lab by validating access through sign-in and audit logs, reviewing how identity integrates with Azure security, and confirming that authentication and authorization are working as expected.
