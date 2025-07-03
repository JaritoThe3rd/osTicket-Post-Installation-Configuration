# osTicket Lab Setup Guide

This guide walks you through configuring a local **osTicket** help desk system for demonstration, learning, or internal use. It covers setup for roles, departments, teams, agents, users, SLAs, and help topics.

---

## Access URLs

- **Admin/Analyst Login Page**: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
- **End User Portal**: [http://localhost/osTicket](http://localhost/osTicket)

---

## Agent Panel vs Admin Panel

- **Agent Panel**: Used by agents to manage tickets, view users, and respond to requests.
- **Admin Panel**: Used to configure system settings, manage permissions, departments, SLAs, and more.

---

## Configure Roles

Roles are used to group permission levels for agents.

- **Location**: `Admin Panel -> Agents -> Roles`
- **Example Role**: `Supreme Admin`

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
