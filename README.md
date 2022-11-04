

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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/KxsYFub.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go into Admin Panel, select the agent tab, and create a new role. According to osTicket roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/g6J7OcP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a new department called system adminstrators. Since tickets are routed through departments in the help desk, there are many settings that can be set for each department.
</p>
<br />

<p>
<img src="https://i.imgur.com/OnKPC90.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
</p>
<br />



<p>
<img src="https://i.imgur.com/Dk9ssht.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As per osTicket agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile
</p>
<br />



<p>
<img src="https://i.imgur.com/Ti25MVu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Users are able to create accounts, they can also log-in to create a ticket or check a ticket's status.
</p>
<br />



<p>
<img src="https://i.imgur.com/xxg6GKn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed. (i.e SEV A, B, or C)
</p>
<br />

<p>
<img src="https://i.imgur.com/wUkBdDV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
According to osTicket Help Topics will help streamline your end-user’s help desk experience to ensure proper assignment and prompt response to the ticket. Create as many Help Topics as needed and can even nest Help Topics within each other for further breakdown (For example, Human Resources and Human Resources/Payroll.) 
</p>
<br />
