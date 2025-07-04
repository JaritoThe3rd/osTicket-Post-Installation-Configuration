# osTicket Post Installation Demonstration and Configuration


This guide is for navigation and demonstration on how to use osTicketing system whether it's on the admin and consumer side of things that you need to be aware of doing. Which basically covers the navigating and configuring in roles, departments, teams, agents, users, SLA's, and help topics. This will allow you to understand on how to use osTicket more efficiently.


---

## Access URLs

- **Admin/Analyst Login Page**:

  [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

  
- **End User Portal**:


- [http://localhost/osTicket](http://localhost/osTicket)


---


## Agent Panel vs Admin Panel

- **Agent Panel**:


- For managing ticket request, view consumer complaints, and respond to certain type of request.

  
- **Admin Panel**:


- Used to modify system settings, controlling certain permission levels, managing departments, SLA's and a lot more configurable settings.


---

## Configuring Certain Roles

Roles are basically used for assigning certain actions that an agent needs to deal with consumer complaints.


Make a `Supreme Admin` role and make sure that role has permission, task, and knowledgebase checked.
- **Location**: `Admin Panel -> Agents -> Roles`
- **Example Role**: `Supreme Admin`


https://github.com/user-attachments/assets/8304bc36-8407-4b0a-b294-519b05947126


---

## Configure Departments

You knowing how to configure departments will allow the company to focus on certain task that are required to be fixed by the IT department and depending on the problem it can be assigned into a unique department.

- **Examples**:
  - `SysAdmins`
  - `Support`
  - `Networking`

- **Location**: `Admin Panel -> Agents -> Departments`


https://github.com/user-attachments/assets/1b4b6bd9-1396-4070-bce6-b05dcedd8e54


---

## Configure Teams

Teams allow you to **group agents** from different departments for collaboration.

- **Location**: `Admin Panel -> Agents -> Teams`
- **Example Team**: `Online Banking`

---

## User Registration Settings

Control whether unregistered users can create tickets.

- **Location**: `Admin Panel -> Settings -> User Settings`
- **Setting**:
  - Enable: **Require registration and login to create tickets**
  - Disable: **Unregistered users can create tickets**

---

## Configure Agents (Staff Members)

Add agents who will manage and resolve tickets.

- **Location**: `Admin Panel -> Agents -> Add New`
- **Example Agents**:
  - `Jane` – Department: `SysAdmins`
  - `John` – Department: `Support`

---

## Configure Users (Customers)

Add users who will submit tickets.

- **Location**: `Agent Panel -> Users -> Add New`
- **Example Users**:
  - `Karen`
  - `Ken`

---

## Configure SLA (Service Level Agreements)

SLAs define ticket response and resolution deadlines.

- **Location**: `Admin Panel -> Manage -> SLA`
- **Examples**:
  - `Sev-A`: Grace Period: **1 hour**, Schedule: **24/7**
  - `Sev-B`: Grace Period: **4 hours**, Schedule: **24/7**
  - `Sev-C`: Grace Period: **8 hours**, Schedule: **Business Hours**

---

## Configure Help Topics

Help Topics categorize tickets for proper routing and priority.

- **Location**: `Admin Panel -> Manage -> Help Topics`
- **Examples**:
  - `Business Critical Outage`
  - `Personal Computer Issues`
  - `Equipment Request`
  - `Password Reset`

---

## Summary

This lab environment demonstrates a structured help desk setup using osTicket. It includes user roles, departments, teams, SLA policies, and categorized help topics to streamline IT and support workflows.
