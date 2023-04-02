# osTicket-Post-install-Config
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

- PHP

- osTicket (Help Desk Ticketing System)
<p>

<h2>Configuration Steps</h2>
Step 1. Configure roles in the admin panel. Go to:

Admin Panel > Agents > Roles
For testing purposes create the role: Supreme Admin and assign permissions
<p>
-Select<strong> add new role <strong>
<p>
<img src="https://i.imgur.com/Q0cqtHv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- <strong> Name your new role <strong>  
<p>
<img src="https://i.imgur.com/FkdB3L8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- <strong> Assign desired permissions and then click add role. <strong>
<img src="https://i.imgur.com/gQeHxLO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
<br />
<p>
Step 2. Configure the Departments

Admin Panel > Agents > Departments
For testing purposes create the department: System Administrators
<p>
</p>
  - Select <strong>add new department<strong> and name your department, then click <strong>create department<strong>
<p>
<img src="https://i.imgur.com/uPv5eTt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
Step 3. Configure Teams

Admin Panel > Agents > Teams
For the purposes of testing create two teams (Level I Support, Level II Support)
<p>
<img src="https://i.imgur.com/YVk8Aj8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Step 4. Allow anyone to create tickets. Go to:

Admin Panel > Settings > User Settings
Registration Required: Require registration and login to create tickets
<p>
</p>
<img src="https://i.imgur.com/ByxGLUC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
Step 5. Configure Agents (Workers who will work the tickets). Go to:

Admin Panel > Agents > Add New
(Whatever names you choose)
<p>
<img src="https://i.imgur.com/XK1qd7w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

-Set agent password
<p>
5b.
<p>
</p>

<img src="https://i.imgur.com/CJM6fLG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<p>
</br>

-Set department for agent
<p>
5c.
<p>
</p>
<img src="https://i.imgur.com/k16lfCq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<br /> 
  
-Set permissions
<p>
5d.
<p>
</p>
<img src="https://i.imgur.com/aLDuNto.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<br />

-Set team and click create!
<p>
5e.
<p>
</p>
<img src="https://i.imgur.com/gH0rPn4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<br />
Step 6. Go the the agent panel and create new user (Customers who can create a service ticket request). Go to:

Agent Panel > Users > Add New
For the purposes of testing create two users 
<p>
<img src="https://i.imgur.com/frlNIaS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
</p>
<br />
- Enter details for new user
<p>
6b.  
<p>
<img src="https://i.imgur.com/5li4Knj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
- Click create and new user is created!
<p>
6c.
<p>
<img src="https://i.imgur.com/2IGzysR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
- Register the new user, set a password and click create account
<p>
6d. 
<p>
<img src="https://i.imgur.com/en8UEQA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
Step 7. Configure SLA (Service Level Agreements)

Admin Panel > Manage > SLA
For the purposes of testing configure three
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
<p>

<p>
<img src="https://i.imgur.com/l8nwHm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
- Name the plan and set the schedule
<p>
7b.
<p>
<img src="https://i.imgur.com/iVYUceP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
- Once completed it should look like this
<p>
7c.
<p>
<img src="https://i.imgur.com/EMz1W9A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
<p>
<br />

Step 8. Configure Help Topics

Admin Panel > Manage > Help Topics > Add New Help Topic
<p>
For the purposes of testing create four topics
<p> -Business Critical Outage
<p> -Personal Computer Issues
<p> -Equipment Request
<p> -Password Reset
<p>
<img src="https://i.imgur.com/RkI9dSo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
- Once completed it should look like this
<p>
8b.
<p>
<img src="https://i.imgur.com/NAA4E7j.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
