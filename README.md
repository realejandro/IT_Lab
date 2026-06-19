# IT Lab

## Overview

This repository contains my hands-on IT Support, System Administration, Networking, and Cybersecurity lab exercises.

The purpose of this project is to build practical experience with Windows, Linux, networking, troubleshooting, and system administration tasks commonly performed by IT Support Specialists, Help Desk Technicians, System Administrators, and Infrastructure Engineers.

Each lab includes:

* Objectives
* Environment setup
* Commands used
* Screenshots
* Results
* Lessons learned

---

## Current Labs

### Windows Administration

#### User Management

* Create local user accounts
* Modify user accounts
* Enable and disable users
* Manage local groups

#### Password Management

* Reset local user passwords
* Verify account status
* Troubleshoot access issues

#### RunAs

* Execute applications under another user's credentials
* Verify security context using `whoami`
* Test user access without logging out

---

## Planned Labs

### Windows

* Local Users and Groups
* Shared Folders and Permissions
* Event Viewer
* Services Management
* Task Scheduler
* PowerShell Administration
* Windows Security

### Linux

* User and Group Management
* File Permissions
* SSH Configuration
* Package Management
* Services and Processes
* Bash Scripting
* Log Analysis

### Networking

* IP Addressing
* DNS Troubleshooting
* DHCP Configuration
* Network Diagnostics
* Wireshark Packet Analysis
* Routing and Switching Fundamentals

### Active Directory

* Domain Controller Setup
* Organizational Units (OUs)
* Group Policy Objects (GPOs)
* User and Group Administration
* Password Policies

### Cybersecurity

* Security Hardening
* Access Control
* Authentication and Authorization
* Security Monitoring
* Vulnerability Assessment Basics

---

## Lab Environment

### Operating Systems

* Windows 11
* Ubuntu Linux

### Tools

* PowerShell
* Command Prompt
* Git
* GitHub
* VS Code
* Wireshark
* Virtual Machines

---

## Completed Exercise #1

### Local User Administration

#### Objective

Learn how to manage local user accounts in Windows.

#### Tasks Performed

* Created a local user account
* Reset the user's password using `net user`
* Executed Command Prompt as another user using `runas`
* Verified the active user context with `whoami`

#### Commands Used

```cmd
net user userf admin1234

runas /user:userf cmd

whoami
```

#### Outcome

Successfully reset a local user password and launched a command prompt under another user's credentials.

#### Skills Practiced

* User Administration
* Password Management
* Windows Command Line
* User Context Verification
* Basic IT Support Troubleshooting

---

## Goals

* Develop practical IT Support skills
* Build a professional IT portfolio
* Document hands-on labs and troubleshooting scenarios
* Prepare for IT Support, Help Desk, System Administration, and Infrastructure roles

---

## Author

Alejandro Cabrera

GitHub: https://github.com/realejandro
