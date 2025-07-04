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


https://github.com/user-attachments/assets/398e1b34-d40f-4bee-848f-12adb15935a1


---

## Configure Departments

Departments determine **ticket visibility** and **assignment scope**.

- **Location**: `Admin Panel -> Agents -> Departments`
- **Examples**:
  - `SysAdmins`
  - `Support`
  - `Networking`

---

## Configure Teams

Teams allow yo
