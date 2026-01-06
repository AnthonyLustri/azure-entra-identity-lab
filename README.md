# Azure Entra ID – Identity & Access Management Lab

## Overview
This lab demonstrates enterprise identity and access management using Microsoft Entra ID.
It focuses on role-based access control (RBAC), least-privilege design, and identity monitoring
commonly used in real-world Azure environments.

## Business Scenario
An organization requires centralized identity management to:
- Control administrative access
- Delegate responsibilities by job role
- Secure privileged accounts
- Monitor authentication and administrative activity

This lab simulates that environment using Microsoft Entra ID.

## Technologies Used
- Microsoft Entra ID
- Security Groups
- Directory Roles (RBAC)
- Sign-in Logs
- Audit Logs

## 🗂️ Repository Structure
```
azure-entra-identity-lab/
├── README.md
├── walkthrough.md
├── architecture/
│   └── entra-identity-architecture.png
└── screenshots/
    ├── users-created.png
    ├── groups-created.png
    ├── it-admins-members.png
    ├── helpdesk-members.png
    ├── developers-members.png
    ├── it-admin-effective-role.png
    ├── helpdesk-effective-role.png
    ├── first-time-signon.png
    ├── sign-in-logs.png
    └── audit-logs.png
```

## Architecture
![Architecture Diagram](architecture/entra-identity-diagram.png)

## Implementation Summary
- Created users representing IT Admin, Helpdesk, and Developer roles
- Implemented role-based security groups
- Assigned directory roles to groups instead of individual users
- Enforced least-privilege access
- Verified role inheritance
- Reviewed sign-in and audit logs for security visibility

## Security Best Practices Demonstrated
- Group-based role assignments
- Separation of duties
- Least privilege
- Identity monitoring and auditing

## Cost
This lab uses free Microsoft Entra ID features and incurs no Azure charges.

## Author
Anthony Lustri
# Azure Entra ID – Identity & Access Management Lab

## Overview
This lab demonstrates enterprise identity and access management using Microsoft Entra ID.
It focuses on role-based access control (RBAC), least-privilege design, and identity monitoring
commonly used in real-world Azure environments.

## Business Scenario
An organization requires centralized identity management to:
- Control administrative access
- Delegate responsibilities by job role
- Secure privileged accounts
- Monitor authentication and administrative activity

This lab simulates that environment using Microsoft Entra ID.

## Technologies Used
- Microsoft Entra ID
- Security Groups
- Directory Roles (RBAC)
- Sign-in Logs
- Audit Logs

## Implementation Summary
- Created users representing IT Admin, Helpdesk, and Developer roles
- Implemented role-based security groups
- Assigned directory roles to groups instead of individual users
- Enforced least-privilege access
- Verified role inheritance
- Reviewed sign-in and audit logs for security visibility

## Security Best Practices Demonstrated
- Group-based role assignments
- Separation of duties
- Least privilege
- Identity monitoring and auditing

## Cost
This lab uses free Microsoft Entra ID features and incurs no Azure charges.

## Author
Anthony Lustri
