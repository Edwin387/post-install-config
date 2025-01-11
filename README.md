<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Acknowledge the difference between the Agent Panel and Admin Panel.
- Configure Roles to define permissions for agents. 
- Set up Departments to group tickets by areas of responsibility
- Create Teams to pull agents from multiple departments.
- Configure user settings to allow or restrict ticket creation.
- Add Agents (workers) and Users (customers).
- Set up Service Level Agreements (SLAs) for ticket response times.
- Create Help Topics for users to categorize their tickets.f

<h2>Configuration Steps</h2>

<h3>1.) Acknowledge Agent Panel vs Admin Panel</h3>

- The **Agent Panel** is used by agent to work on tickets.
- The **Admin Panel** is used to manage system settings, configurations, and permissions.

  <h3>2.) Configure Roles</h3>

  -Navigate to **Admin Panel -> Agents -> Roles**.
  -Add a new role called **Supreme Admin**.
    -Define permissions for agents based on the role they will have. In this lab, we will give permissions for the Tickets, Tasks, and Knowledgebase sections.

<p>  
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>3.) Configure Departments</h3>

- Navigate to **Admin Panel -> Agents -> Departments**.
- Add a new department called **SysAdmins**.
- Use departments to control ticket visibility and assign areas of responsibility (e.g., Help Desk, SysAdmins, Networking).

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<h3>4.) Configure Teams</h3>

- Navigate to **Admin Panel -> Agents -> Teams**.
- Create a new team called **Online Banking**.
 - Pull agents from different departments to form specialized teams.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>5.) Allow Anyone to Create Tickets</h3>

- Navigate to **Admin Panel -> Settings -> User Settings**.
- Uncheck **Require registration and login to create tickets** to enforce ticket creation by anyone.
-Enable **Public - Anyone can register** to disable requiring users to register and log in before creating tickets. 

<p>
</p>
<br />

<h3>6.) Configure Agents</h3>

- Navigate to **Admin Panel -> Agents -> Add New**.
- Add agents with the following details:
- **Jane**: Assigned to the **SysAdmins** department.
- **John**: Assigned to the **Support** department.

<p>
  
</p>

<p>
  
</p>

<p>
  
</p>

<p>
  
</p>

<h3>7.) Configure Users</h3>

- Navigate to **Agent Panel -> Users -> Add New**.
- Add users with the following details:
- **Karen**
- **Ken**

<p>
  
</p>

<h3>8.) Configure SLA (Service Level Agreements)</h3>

- Navigate to **Admin Panel -> Manage -> SLA**.
- Add the following SLAs:
- **Sev-A**: Grace Period = 1 hour, Schedule = 24/7.
- **Sev-B**: Grace Period = 4 hours, Schedule = 24/7.
- **Sev-C**: Grace Period = 8 hours, Schedule = Business Hours.

<p>
    
</p>

<p>
  
</p>

<p>
  
</p>

<h3>9.) Configure Help Topics</h3>

- Navigate to **Admin Panel -> Manage -> Help Topics**.
- Add the following help topics for users to select when creating a ticket:
- **Business Critical Outage**
- **Personal Computer Issues**
- **Equipment Request**
- **Password Reset**
- **Other**

<p>
  
</p>

<h2>Conclusion</h2>

By completing the post configuration steps, you have successfully customized osTicket to suit your organizations's requirements. You are now ready to start using osTicket to manage and resolve customer issues efficiently. 
