# Active Directory Configuration

## Overview
Deployed Active Directory Domain Services on Windows Server 2022.

## Domain
- Domain name: homelab.local
- Domain Controller: DC01 (192.168.10.1)

## Organizational Units
- IT_Department
- HR_Department

## Users Created
- jan.kowalski (IT_Department)
- anna.nowak (HR_Department)
- piotr.wisniewski (IT_Department)

## Group Policy Objects
- IT_Security_Policy applied to IT_Department
  - Minimum password length: 8 characters
  - Password complexity: Enabled

## Screenshots
![AD Users](ss1.jpg)
*Active Directory users created in homelab.local domain*

![OU Structure](ss2.jpg)
*Organizational Units — IT_Department and HR_Department*

![GPO](ss3.jpg)
*IT_Security_Policy GPO linked to IT_Department*

![Server IP](ss4.jpg)
*Windows Server 2022 static IP configuration — 192.168.10.1*

![Domain Properties](ss6.jpg)
*Windows 10 joined to homelab.local domain*

![GPO Result](ss7.jpg)
*GPO successfully applied on domain client — verified with gpresult*
