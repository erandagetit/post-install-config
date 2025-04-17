# post-install-config<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Acknowledge the difference between the Agent Panel and Admin Panel.
- Configure Roles to define permissions for agents.
- Set up Departments to group tickets by areas of responsibility.
- Create Teams to pull agents from multiple departments.
- Configure user settings to allow or restrict ticket creation.
- Add Agents (workers) and Users (customers).
- Set up Service Level Agreements (SLAs) for ticket response times.
-Create Help Topics for users to categorize their tickets.
<h2>Configuration Steps</h2>

1.) Acknowledge Agent Panel vs Admin Panel
- The Agent Panel is used by agents to work on tickets.
- The Admin Panel is used to manage system settings, configurations, and permissions.
2.) Configure Roles
  Navigate to Admin Panel -> Agents -> Roles. Add a new role called Supreme Admin.
</p>
- Define permissions for agents based on the role they will have. In this lab, we will give permissions for the Tickets, Tasks, and Knowledgebase sections.
</p>
<img src=https://i.imgur.com/99HMtd9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/sWaCEnc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/Dd9WPGK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/uzEcMCi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
3.) Configure Departments
- Navigate to Admin Panel -> Agents -> Departments.
- Add a new department called SysAdmins.
 - Use departments to control ticket visibility and assign areas of responsibility (e.g., Help Desk, SysAdmins, Networking).

 <img src=https://i.imgur.com/HgJAdRy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
4.) Configure Teams
- Navigate to Admin Panel -> Agents -> Teams.
- Create a new team called Claims Intake.
 - Pull agents from different departments to form specialized teams.
</p>
 <img src=https://i.imgur.com/5C5wPqg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
5.) Allow Anyone to Create Tickets
- Navigate to Admin Panel -> Settings -> User Settings.
- Uncheck Require registration and login to create tickets to enforce ticket creation by anyone.
- Enable Public - Anyone can register to disable requiring users to register and log in before creating tickets.
</p>
<img src=https://i.imgur.com/ghFjYiS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
6.) Configure Agents (Workers)
- Navigate to Admin Panel -> Agents -> Add New.
- Add agents with the following details:
 - Jane: Assigned to the SysAdmins department.
 - John: Assigned to the Support department.
</p>
<img src=https://i.imgur.com/DeTKLZi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
You can choose to set their password or send the agent a password reset email.
<img src=https://i.imgur.com/pI77IcQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/qJKORE9.png=" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/wb1vIhj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/DBqaP8R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/hgfaKcW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/6WaQ2mj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
7.) Configure Users (Customers)
- Navigate to Agent Panel -> Users -> Add New.
- Add users with the following details:
 - Karen
 - Ken 
</p>
 <img src=https://i.imgur.com/eKau7eD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/JKiXiQy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
8.) Configure SLA (Service Level Agreements)
- Navigate to Admin Panel -> Manage -> SLA.
- Add the following SLAs:
 - Sev-A: Grace Period = 1 hour, Schedule = 24/7.
 - Sev-B: Grace Period = 4 hours, Schedule = 24/7.
 - Sev-C: Grace Period = 8 hours, Schedule = Business Hours.
<p>

<img src="https://i.imgur.com/YVI68UP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/HNybpp5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MplbkTV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/BMkhz3y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

 9.) Configure Help Topics
- Navigate to Admin Panel -> Manage -> Help Topics.
- Add the following help topics for users to select when creating a ticket:
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<img src="https://i.imgur.com/PC2sKAO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/JN0GRCJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
Conclusion
By completing the post-installation configuration steps, you have successfully customized osTicket to suit your organization's requirements. 
You are now ready to start using osTicket to manage and resolve customer issues efficiently.
<p>

</p>
<p>

</p>
<br />
