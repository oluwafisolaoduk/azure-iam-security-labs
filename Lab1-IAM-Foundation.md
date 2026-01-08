# Lab 1: Azure IAM Foundation – Users, Groups, and RBAC

## Objective
To design and implement a foundational Identity and Access Management (IAM) model in Azure using Microsoft Entra ID, following least-privilege and enterprise security best practices.

---

## Environment
- Azure Portal
- Microsoft Entra ID
- Azure Subscription (Free/Trial)

---

## Tasks Performed

### 1. User Creation
- Created one administrative user account for cloud administration.
- Created two standard user accounts for regular access.
- Ensured no direct administrative privileges were assigned to standard users.

### 2. Group-Based Access Control
- Created security groups to manage access at scale:
  - **Cloud-Admins** – for administrative users
  - **App-Users** – for standard users
- Assigned users to groups instead of assigning permissions directly.

### 3. Role-Based Access Control (RBAC)
- Assigned Azure RBAC roles at the subscription level:
  - **Contributor** role assigned to the *Cloud-Admins* group
  - **Reader** role assigned to the *App-Users* group
- Verified that access permissions were inherited through group membership.

---

## Security Concepts Applied
- Least Privilege Access
- Role-Based Access Control (RBAC)
- Group-based identity management
- Separation of duties

---

## Real-World Relevance
This lab reflects how enterprise environments manage identity and access by:
- Avoiding direct role assignments to individual users
- Using security groups for scalable permission management
- Reducing security risk through least-privilege enforcement

---

## Outcome
A secure and scalable IAM foundation was successfully implemented, ensuring users can access Azure resources only according to their assigned roles and responsibilities.

---
