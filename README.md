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

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Departments
- Teams
- Allow creation of Tickets
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<strong>Step 1:</strong> Setting up <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a>

<p>
Roles are permissions granted to Agents for each department they have access to. Each Role has it's own permissions that can be granted/denied for Agents
  who have that Role in association with deparments they have access to.
<br />
<br />
To start off we will create a role named "Supreme Admin" 
<br />
<br />
In the permissions tab just check mark everything, but take a moment to observe the multiple permissions roles can be assigned.
<br />
<br />
(Admin Panel) Agents ⇒ Roles
</p>

<p>
<img src="https://i.imgur.com/QlbCCtj.png" height="80%" width="80%" alt="Permissions"/>
</p>

<p>
<img src="https://i.imgur.com/3XF1mXw.png" height="80%" width="80%" alt="Setting Roles"/>
</p>

<br />

<strong>Step 2:</strong> Setting up <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html">Departments</a>
<p>
Tickets are routed through Departments and there are many settings that can be set for each Department (Check documentation).
<br />
<br />
After creating a Role, right next to it is the Departments tab which we will be utilizing for this step.
<br />
<br />
Create a new Department named whatever you'd like, but for this example I will use "Systems Admin", leave everything else as default settings.
<br />
<br />
Take a minute to observe all the fields in each section of adding a new department
<br />
<br />
(Admin Panel) Agents ⇒ Departments
</p>
<p>
<img src="https://i.imgur.com/Kkxhu6V.jpg" height="80%" width="80%" alt="Added Department"/>
</p>
<p>
<img src="https://i.imgur.com/KWppJOb.png" height="80%" width="80%" alt="Added Department"/>
</p>

<br />
<br />
<br />

<strong>Step 3:</strong> Setting up <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">Teams</a>
<p>
Teams allow the use of pulling Agents from different departments to organize them to handle spcific issues via Help Topic or Ticket Filter.
<br />
<br />
Add a new Team and name it whatever you'd like, for this example I will add "Level II Support" since level I is created by default.
<br />
<br />
(Admin Panel) Agents ⇒ Teams ⇒ Add New Team
</p>

<p>
<img src="https://i.imgur.com/QxdeVSr.png" height="80%" width="80%" alt="Adding Team"/>
</p>

<br />
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration END</h1>
