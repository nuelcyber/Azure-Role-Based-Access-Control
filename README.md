# Azure-Role-Based-Access-Control

# Azure Role-Based Access Control Implementation Lab

## Project Overview

This project demonstrates the implementation of **Role-Based Access Control (RBAC)** in Microsoft Azure.  

The lab showcases how to:

- Create Microsoft Entra ID (Azure AD) security groups
- Assign users to groups
- Implement role-based permissions at subscription scope
- Enforce the Principle of Least Privilege
- Manage identities using Portal, PowerShell, and CLI

All resources were deployed in the **West US** region.


## Lab Objectives

- Create Senior Admins group and add Joseph Price using the Azure Portal
- Create Junior Admins group and add Isabel Garcia using PowerShell 
- Create Service Desk group and add Dylan Williams using the Azure CLI
- Assign Virtual Machine Contributor role to the Service Desk group  
- Test the implemented access control


## Technologies & Services Used

- Microsoft Entra ID (Azure AD)
- Azure Role-Based Access Control (RBAC)
- Azure Portal
- Azure PowerShell
- Azure CLI
- Subscription-level role assignments



# Implementation Walkthrough

## Creating the Senior Admins Group using Azure Portal

Steps performed:

1. Navigated to Microsoft Entra ID
2. Created a new Security Group named Senior Admins
3. Added user Joseph Price as a member

Demonstrates manual identity and group management using the Azure Portal to implement structured administrative access.

<p align="center"><strong>Figure 1: Senior Admins Group Creation</strong></p>

<p align="center">
  <img src="images/senior-admins.png" width="700" height="400">
</p>

## Creating the Junior Admins Group using Azure Powershell

Steps performed:

1. Navigated to Azure Powershell
2. Created a new Security Group named Junior Admins
3. Added user Isabel Garcia as a member

This demonstrates manual identity and group management using the Azure Portal to implement structured administrative access.

## Creating the Service Desk Group using Azure CLI

Steps performed:

1. Navigated to Azure CLI
2. Created a new Security Group named Service Desk
3. Added user Dylan Williams as a member


## Assigning the Virtual Machine Contributor Role to the Service Desk Group

Steps performed:

1. Navigated to Azure Portal
2. Opened Subscriptions and selected the appropriate subscription
3. Clicked on Access Control (IAM)
4. Selected Add role assignment
5. Chose the Virtual Machine Contributor role
6. Selected Service Desk group as the member
7. Reviewed and clicked Assign to complete the role assignment


## Why Assign Roles to Groups Instead of Users?
- Improves scalability
- Simplifies onboarding/offboarding
- Reduces administrative overhead
- Supports Zero Trust architecture
- Enhances auditability


## Security Concepts Demonstrated
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Subscription-level scope control
- Delegated administration
- Automation using PowerShell & CLI
- Principle of Least Privilege
- Access governance best practices


## Skills Demonstrated
- Azure identity governance
- RBAC configuration and enforcement
- Cloud access control implementation
- PowerShell automation
- Azure CLI administration
- Secure delegation of privileges


## Real-World Enterprise Relevance
In enterprise cloud environments, improper access control is a leading cause of breaches.
RBAC ensures:
- Controlled privilege distribution
- Reduced attack surface
- Compliance with governance standards
- Prevention of privilege escalation
- Clear separation of duties
- This lab reflects production-grade cloud security practices used in corporate environments.


## Conclusion
This lab demonstrates practical implementation of Azure RBAC using multiple management interfaces while enforcing structured identity governance.
It highlights secure access delegation and cloud security best practices relevant to:
- Cloud Security Engineer
- Azure Administrator
- IAM Analyst
- SOC Analyst
