
# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
This project use a fictional company, Northstar Medical Group, to simulate real-world IT support and system administration tasks for educational purposes. After ending its contract with a Managed Service Provider (MSP), the companywas left with apoorly managed Active Directory environment containing inconsistent naming conventions, disorganized Organization Units (OUs), incorrect user placements, and improper security group assignments.Additional issues include active accounts for former employees, missing documentation, and inconsistent administrative practice that have led to configuration drift. The objective of home lab is to assess, organized, and maintain the active Directory infrastructure using industry best practices.
 
## Solution Overview
- A structure  remediation plan was omplemented to improve the stability, security, and organization of Northstar Medical Grou's Active Directory environment.
- A new Windows server 2022 domain controller was deployed, and Organization Units (OUs), security groups, and Uusers accounts were configured according to the company's department structure and role-based access control (RBAC) best practices.
- Simulated Help Desk ticket were used to identify, troubleshoot, and resolve issue of a user that was placed in the incorrect department then get assigned to the incorrect security group. 


## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

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
