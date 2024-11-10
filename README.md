<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=thl4tI3eKXY)
<h2>Video Demonstration</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure (Roles, Departments, and Teams)
- Allow anyone to create tickets
- Configure (Agents/Workers, and Users/Customers)
- Configure SLA
- Configure help topics 

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_roles_lab_3_part_2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_Department_lab_3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_teams_lab_3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logged in as the admin, I Configured roles to create a new supreme admin role, getting all permissions. Configured departments and created a systems admin department. Configured teams to be able to pull specefic teams to perform specefic tasks. Created a level 1 and level 2 support
</p>
<br />

<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/Allow_anyone_to_create_tickets_lab_3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets.
*Registration required: required registration and login to create tickets
</p>
<br />

<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_agents_lab_3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an admin I Configured agents; these are the workers. They have the intent to respons to tickets. Added John and Jane Doe with different permissions
</p>
<br />

<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_users_lab_3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configured users; these are the customers the agents will support. Added Karen and Ken Dow
</p>
<br />

<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_SLA_lab_3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an admin I Configured SLA (with osTicket, it is used as a time limit to finish such tasks). Create 3 SLA's, Sev-A (1 hour, 24/7), Sev-B (8 hours, 24/7), and Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://github.com/kleeloy/post-install-config/blob/main/Diagrams/configure_help_topics_lab_3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an admin I Configured help topics; this helps the end users choose wht they need help with. Created 'Business Critical Outage', 'Personal Computer Issues', 'Equipment Request', 'Password Reset' 
</p>
<br />
