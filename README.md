# osTicket-Post-install-Config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines and walks you through the post-install configuration of the open-source help desk ticketing system osTicket.<br />



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

Create the role: Supreme Admin and assign permissions
<p>
-Select<strong> add new role <strong>
<p>
<img src="https://i.imgur.com/876i9Ab.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
1b. Name the role
<p>
<img src="https://i.imgur.com/PAfrKn2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
<p>
1c.<strong> Assign desired permissions and then click "add role". <strong>
<p>
<img src="https://i.imgur.com/LvvLaLQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
<br />
<p>
Step 2. Configure the Departments

Admin Panel > Agents > Departments
<p>
Create the department: System Administrators
<p>
</p>
- Select <strong>add new department<strong> and name your department, then click <strong>create department<strong>
<p>
<img src="https://i.imgur.com/djtXuXr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
Step 3. Configure Teams<p>

Admin Panel > Agents > Teams
<p>
Create two teams (Level I Support, Level II Support)
<p>
<img src="https://i.imgur.com/EZ6PxKd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Step 4. Allow anyone to create tickets.<p> 
Go to: Admin Panel > Settings > User Settings
<p>
Registration Required: Require registration and login to create tickets
<p>
</p>
<img src="https://i.imgur.com/nBwdz7v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
Step 5. Configure Agents (Agents who will work the tickets).<p>

Go to: Admin Panel > Agents > Add New Agent
<p>
- Add agents name
<p>
- Set Password
<p>
<img src="https://i.imgur.com/iu2Pkqb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
5b. Set agent password
<p>
</p>

<img src="https://i.imgur.com/z3t8gRN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<p>
</br>

<p>
5c. Set department for agent
<p>
</p>
<img src="https://i.imgur.com/AiIvj9K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<br /> 
  
<p>
5d. Set permissions
<p>
</p>
<img src="https://i.imgur.com/sFfl3e1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<br />

<p>
5e. Set team and click create!
<p>
</p>
<img src="https://i.imgur.com/OvBK5qq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>
<br />
Step 6. Go to Agent Panel to create new user (Allowing clients to create service ticket requests).<p>

<p>
<img src="https://i.imgur.com/7RayKgo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
</p>
<br />

6b. Add New
<p>
<img src="https://i.imgur.com/tZcGe0l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
  
6c. Enter details for new user and click add user 
<p>
<img src="https://i.imgur.com/fCQ1wsN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
6d. New user needs to be registered. Go ahead and click "Register"
<p>
<img src="https://i.imgur.com/Mm0TGui.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />


6e. Set a password and click create account
<p>
<img src="https://i.imgur.com/Wnxee5J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
  
Step 7. Configure SLA (Service Level Agreements)<p>

Admin Panel > Manage > SLA > Add New SLA Plan
For the purposes of testing configure three
<p>Sev-A (1 hour, 24/7)
<P>Sev-B (4 hours, 24/7)
<p>Sev-C (8 hours, business hours)
<p>

<p>
<img src="https://i.imgur.com/ZEVGBgU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
 
<p>
7b. Name the plan and set the schedule
<p>
<img src="https://i.imgur.com/vu0nOX7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
 
<p>
7c. Once completed it should look like this
<p>
<img src="https://i.imgur.com/EMz1W9A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
<p>
<br />

Step 8. Configure Help Topics

Admin Panel > Manage > Help Topics > Add New Help Topic
<p>
Create four topics. Example:
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

<p>
8b. Once completed it should look like this
<p>
<img src="https://i.imgur.com/NAA4E7j.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
                                                                                                
<p>
<strong> Thank you for following along. <strong>
