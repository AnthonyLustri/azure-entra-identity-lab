# Walkthrough – Azure Entra ID Identity & Access Lab

## Step 1: User Creation
Three users were created to represent common enterprise roles:
- IT Administrator
- Helpdesk User
- Developer User

![Users Created](screenshots/users-created.png)

---

## Step 2: Security Group Creation
Security groups were created for role-based access:
- IT-Admins
- Helpdesk
- Developers

All groups use assigned membership.

![Groups Created](screenshots/groups-created.png)

---

## Step 3: Group Membership
Users were added to the appropriate groups based on job role:
- IT Administrator → IT-Admins
- Helpdesk User → Helpdesk
- Developer User → Developers

![IT Admins Members](screenshots/it-admins-members.png)  
![Helpdesk Members](screenshots/helpdesk-members.png)  
![Developers Members](screenshots/developers-members.png)

---

## Step 4: Role-Based Access Control (RBAC)
Directory roles were assigned to groups:
- IT-Admins → Global Reader
- Helpdesk → User Administrator
- Developers → No directory role

Role inheritance was verified at the user level.

![IT Admin Effective Role](screenshots/it-admin-effective-role.png)  
![Helpdesk Effective Role](screenshots/helpdesk-effective-role.png)

---

## Step 5: Authentication & Monitoring
Authentication activity was generated through user sign-ins, including first-time sign-in behavior.
Sign-in and audit logs were reviewed to confirm visibility into authentication and administrative actions.

![First Time Sign-in](screenshots/first-time-signon.png)  
![Sign-in Logs](screenshots/sign-in-logs.png)  
![Audit Logs](screenshots/audit-logs.png)
