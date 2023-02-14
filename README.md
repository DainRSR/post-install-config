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

- Configure Roles
- Configure Departments & Teams
- Configure Agents & Users
- Configure SLA (service learning agreements)
- Configure Helpdesk Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/jSyQqvE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. We will create roles as Admin and distributing them to Agents on the Helpdesk team. To see more information about roles checkout this link https://docs.osticket.com/en/latest/Admin/Agents/Roles.html . Go to the Admin Panel, click agents and then roles. We can now 'Add New Role'. You can name it Supreme Admin or whatever you want for this practice lab. Then go to permissions and you will see 'Tickets, Tasks, Knowledgbase' just select everything from each of those groups and then click Add Role. This user of Supreme Admin will be able to do everything and assign permissions to others. 
</p>
<br />

<p>
<img src="https://i.imgur.com/x85AaS2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Next we will create a 'Department'. The departments will determine how the tickets get placed depending on the issue at hand. Go to Admin Panel, Agents and then Department and add a new department. Only make the changes you see in the image. We will configure the SLA's later. Scroll down an click create department. To learn more about departments you can checkout this link https://docs.osticket.com/en/latest/Admin/Agents/Departments.html

2.1 Now we will create our 'Teams', which will allow us to get agents from different departments to fix issues. Go to Admin panel, Agents, Teams and then Add new team. You can name your team 'Level II Support'. Click on members and you can add yourself to this team for now since we have not created other memebers yet.   
<br />

<p>
<img src="https://i.imgur.com/DYxhphC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3.0 Now lets create 'Agents', these are the helpdesk individuals that will help solve tickets. Go to Admin panel, Agents and click add new agent. You can name your agents whatsveer you choose. Just remeber their credentials for when we need it to log in as them and respond to tickets. Create a name, email and username. Then click set password to create a password for your Agent. Uncheck both boxes, create password and press ok. Go to Access and set department to 'System Administrators' and the role will be 'Supreme Admin' and go to teams and set to Level II Support that we created. Click create and go back to Agents and create another one. 
</p>
<br />
