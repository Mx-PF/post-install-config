<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%" alt="osTicket logo"/>
</p>

# Easy Guide: Setting Up osTicket After Installation

This guide helps you configure osTicket after you’ve installed it. We’ll set up roles, teams, and other important settings so your help desk can start working smoothly.

## Tools You’ll Use
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

## Operating System
- Windows 10 (21H2)

## What You’ll Set Up
- Roles (like admin permissions)
- Departments (like IT or Support)
- Teams (groups of agents)
- Agents (the people who solve tickets)
- Users (the customers who submit tickets)
- SLA (service level agreements for response times)
- Help Topics (categories for tickets)

## Step-by-Step Instructions

### Step 1: Set Up Roles
- Go to **Admin Panel** > **Agents** > **Roles**.
- Create a role called **Supreme Admin** with full permissions.  
  <img src="https://i.imgur.com/SXpTf20.png" height="75%" width="100%" alt="Definitions"/>  
  <img src="https://i.imgur.com/9fBmrZj.png" height="75%" width="100%" alt="Permissions"/>  
  <img src="https://i.imgur.com/1sDBsuZ.png" height="75%" width="100%" alt="More Permissions"/>  
  <img src="https://i.imgur.com/2SVt7rt.png" height="75%" width="100%" alt="Even More Permissions"/>  
  <img src="https://i.imgur.com/vJl5MPw.png" height="75%" width="100%" alt="Sys Admin Success"/>

---

### Step 2: Set Up Departments
- Go to **Admin Panel** > **Agents** > **Departments**.
- Create a department called **System Administrators**.  
  <img src="https://i.imgur.com/83gWQsO.png" height="75%" width="100%" alt="System Administrators"/>  
  <img src="https://i.imgur.com/oGLXmQv.png" height="75%" width="100%" alt="System Administrators"/>

---

### Step 3: Set Up Teams
- Go to **Admin Panel** > **Agents** > **Teams**.
- Create a team called **Level II Support**.  
  <img src="https://i.imgur.com/BnPrcDH.png" height="75%" width="100%" alt="Level II Support"/>

---

### Step 4: Allow Anyone to Create Tickets
- Go to **Admin Panel** > **Settings** > **User Settings**.
- Make sure "Require registration and login to create tickets" is **not** checked.  
  <img src="https://i.imgur.com/QsJjOuM.png" height="75%" width="100%" alt="ticket creations"/>

---

### Step 5: Set Up Agents (Workers)
- Go to **Admin Panel** > **Agents** > **Add New**.
- Create agents like **Jane Doe** and **John Doe**. Assign them to departments and teams as needed.  
  <img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="agent one access"/>  
  <img src="https://i.imgur.com/NcCP0v9.png" height="75%" width="100%" alt="agent two"/>  
  <img src="https://i.imgur.com/aKTJ01A.png" height="75%" width="100%" alt="agent two access"/>

---

### Step 6: Set Up Users (Customers)
- Go to **Admin Panel** > **Users** > **Add New**.
- Create users like **Ken User** and **Karen User**.  
  <img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="user access"/>

---

### Step 7: Set Up SLA (Service Level Agreements)
- Go to **Admin Panel** > **Manage** > **SLA**.
- Create three SLAs:
  - **Sev-A** (1 hour, 24/7)
  - **Sev-B** (4 hours, 24/7)
  - **Sev-C** (8 hours, business hours)  
  <img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="sev one"/>  
  <img src="https://i.imgur.com/izcD74X.png" height="75%" width="100%" alt="sev two"/>  
  <img src="https://i.imgur.com/xKzdp7w.png" height="75%" width="100%" alt="sev three"/>

---

### Step 8: Set Up Help Topics
- Go to **Admin Panel** > **Manage** > **Help Topics**.
- Create topics like:
  - **Business Critical Outage**
  - **Personal Computer Issues**
  - **Equipment Request**
  - **Password Reset**  
  <img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="business critical outage"/>  
  <img src="https://i.imgur.com/3Y7k2o1.png" height="75%" width="100%" alt="personal computer issues"/>  
  <img src="https://i.imgur.com/Z0eIGea.png" height="75%" width="100%" alt="equipment request"/>  
  <img src="https://i.imgur.com/ndOdtTZ.png" height="75%" width="100%" alt="password reset"/>

---

### 🎉 All Done! 🎊
Your osTicket is now fully set up. Practice creating and solving tickets to get comfortable—this is a key skill for any help desk specialist!
