
# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
This project use a fictional company, Northstar Medical Group, to simulate real-world IT support and system administration tasks for educational purposes.
"After ending his contract with a Managed Service Provider (MSP), the company was left with a poorly managed Active Directory environment containing inconsistent naming conventions, disorganized Organization Units (OUs), incorrect user placements, and improper security group assignments. Additional issues include active accounts for former employees, missing documentation, and inconsistent administrative practice that have led to configuration drift". The objective of this home lab is to assess, organized, and maintain the active Directory infrastructure using industry best practices.
 
## Solution Overview
- A structure  remediation plan was implemented to improve the stability, security, and organization of Northstar Medical Group's Active Directory environment.
- A new Windows server 2022 domain controller was deployed.
- Organization Units (OUs), security groups, and Users accounts were configured according to the company's department structure and role-based access control (RBAC) best practices.
- Simulated Help Desk ticket were used to identify, troubleshoot, and resolve issue of a user that was placed in the incorrect department, and assigned to the incorrect security group. 


## Video Walkthrough
https://www.loom.com/share/a910fc15448a4f809fd93200612b063e

## Tools Used
* Windows Server 2022
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security group mapped to each department
* Provisioned 15 users accounts with consistent naming conventios and attribute standards
* Solved a mock ticket where a user was given the incorrect access
* Fully documented all my steps
