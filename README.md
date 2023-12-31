<p align="center">
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

- Configure Roles, Departments, Teams
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure SLA (Service Level Agreements)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/zgxMOOH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/fUhzevR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/3oH5wua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a new role (called Supreme) Admin through Admin Panel> Agents> Roles. 
Roles are the permissions to agents or different departments to have access. For effective access, I enabled permissions which includes Ticket options, tasks and knowledgebase.

Departments:  Created new departments (called System Administrators) through Admin Panel> Agents> Departments.
Since tickets routes from various department inorder to provide solutions or attentions within certain hours such as SLA tickets. 

Teams: Creating teams allows extracting tickets from different groups or per categories. 
I created a new teams (called Level II support and Level III support) through Admin panel > Agents > Teams
</p>
<br />

<p>
<img src="https://i.imgur.com/cM2t6l1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For ticket creation, I enabled the registration and login to create ticket through Admin panel > settings > User, then I enabled it.
I created a new agents name Jane Smith and John Doe, assigned them to a primary department created earlier by me (Maintaenance/system adminstrators, under role Supreme) 
granted permissions and placed in teams (Level II and III support) respectively.</p>
<br />

<p>
<img src="https://i.imgur.com/PHaNtVT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Users are customers or owners of the ticket in the help desk. So I created users through the agent panel > Users > User Directory.
I used Jane Smith admin account to create the new users (Ken Ken and Ope Ope)</p>
<br />

<p>
<img src="https://i.imgur.com/6LqByKP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plan (Service Level Agreements) in this opinion is like time or period set in place for tickets resolved or closed. 
It is alloted time or amount plan passed for the completion on the task according to tickets' priorities.
So to configure a new  SLA Plans, go to Admin panel >. manage> SLA plan. I created Sev-A (1 hour), Sev-B (4 hours) and Sev-C (8hours) in this session. </p>
<br />

<p>
<img src="https://i.imgur.com/whQxugJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Basically, help topics is more like grouping issues or tickets that have simialr or related problem together.
Tickets can be group according to department issues such as missing equipments, Password reset, Business critical outage and so on. 
So to configure Help Topics, I created new help topics through Admin panel > Manage > Help Topics. New help topics created includes;
Business Critical Outage, Password Reset, Personal Computer Issues and Equipment Request.</p>
<br />
