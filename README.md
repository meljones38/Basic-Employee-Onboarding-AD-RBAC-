# Basic Employee Onboarding – Active Directory & RBAC Lab

## Project Overview

This project simulates an Identity and Access Management (IAM) environment for a fictional healthcare organization, **Northstar Medical Group**.

The lab demonstrates the process of configuring an Active Directory domain, organizing users by department, provisioning employee accounts, implementing Role-Based Access Control (RBAC), managing security group membership, and troubleshooting access issues.

## Technologies Used

- Windows Server
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- Organizational Units (OUs)
- Security Groups
- Role-Based Access Control (RBAC)
- VirtualBox
- GitHub

## IAM Skills Demonstrated

- User account provisioning
- Identity lifecycle administration
- Organizational Unit management
- Security group creation and administration
- Group-based access management
- Role-Based Access Control (RBAC)
- Principle of Least Privilege
- Access troubleshooting
- User access remediation
- Technical documentation
- Incident resolution

## Environment

A fictional healthcare organization called **Northstar Medical Group (NMG)** was created to simulate a business Active Directory environment.

Departmental OUs were configured for:

- Finance
- Human Resources
- Information Technology
- Operations

Users were assigned to the appropriate organizational units and security groups based on their job functions.

## RBAC Implementation

Department-based security groups were used to implement Role-Based Access Control.

Examples include:

- Finance-Users
- HR-Users
- IT-Users
- Operations-Users

This structure demonstrates how access can be assigned according to job responsibilities instead of granting permissions directly to individual users.

## Incident Resolution

An access issue involving employee **Jane Cooper** was investigated.

The user had been incorrectly placed in the Operations OU and Operations-Users security group instead of Human Resources.

The issue was resolved by:

1. Removing the incorrect Operations group membership.
2. Moving the account to the HR OU.
3. Adding the user to the HR-Users security group.
4. Verifying the corrected account placement and group membership.

This demonstrates basic IAM troubleshooting, access remediation, and least-privilege administration.

## Repository Structure

**Documentation/**  
Contains documentation for the domain configuration, users, security groups, and RBAC structure.

**Incident-Reports/**  
Contains documentation of IAM/access incidents and their resolution.

**Screenshots/**  
Contains screenshots demonstrating the Active Directory configuration and completed lab activities.

## Project Purpose

This lab was created to develop hands-on experience with Active Directory and Identity and Access Management concepts used in enterprise IT environments, including user provisioning, access control, RBAC, security groups, troubleshooting, and documentation.

## Lab Evidence

The Screenshots directory contains visual evidence of the completed Active Directory and IAM lab activities, including:

- Active Directory domain configuration
- Organizational Unit (OU) structure
- Employee user account provisioning
- Department-based security groups
- Role-Based Access Control (RBAC) implementation
- User and group membership verification
- Access troubleshooting and remediation

These screenshots demonstrate hands-on experience with identity administration, access provisioning, group-based authorization, and least-privilege access management.
