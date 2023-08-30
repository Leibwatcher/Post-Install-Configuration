# Post-Install-Configuration<p align="center">
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

- Login to the osTicket Admin Panel 
- Configure Roles
- Configure Departments
- Configure Teams
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Login with your user name and password into the osticket Admin Panel. Below is the admin/helpdesk User Interface (UI) that are in this ticketing sysem and also were the tickets are reflected that are created by the end user.
  
![Annotation 2023-08-06 180047](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/26ca9d8e-e870-49cd-ba82-113dc21f0fc5)

</p>
<p>

Configure [Roles]

First step is to "Configure Roles". This step gives granted permissions to Agents per Department that will allow them to access. Agents can have unlimmited number of Roles, which permissons can be checked and unchecked at anytime.
1. Go to Admin Panel----> Agents----> Add new Roles

2. Set agent's name to Supreme Admin


Now we can enbable "Permissions" and since this is "Supreme Admin" all possible permissions are available.

![Annotation 2023-08-06 174259](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/975fd45d-a5d1-4a2d-9324-1b78cb6e9f79)

Congfigure [Departments]

Tickets are set through Departments in the help desk world, there are many settings that can be set for each Departments.

1. Admin panel--->Agents---->Deparments
2. Then System Admininstrators
3. Keep the remaining fields on default and review the selection that are available to choose from.

![Annotation 2023-08-06 174718](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/419e6a62-72d9-4322-b10a-db69f3b9868a)

Configure [Teams]

Teams give you the ability to pull Agents from different Deparments to work on specific issues or ticket Filter.

1. Admin Panel---->Agents----->Teams
2. Level 1 Support
3. level 2 Support

In "User Settings" anyone is allowed to create a ticket
It may be required for users registrator so they can create tickets, this help prevent random ticket or to limit Users accessibility to the help desk.

1.Admin Panel--->Settings---->User Settings
2. Click on and enable "Registration Required" Note not for this lab keep it unchecked.


   ![Annotation 2023-08-06 175027](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/de380111-fdd6-4a66-a8a2-50833dd876cc)

Configure [Agents (workers)]

Creating and giving access to your "Agents(Worker)" to resovle tickets. They need to be assgined to deparments and a primary role for the tickets that will arise. Agents can be roled in more than one department and assigned to different rolesto thise departments; this could be configured in the access tab of the Agents's Profile.


Admin Panel---->Agents---->Add New

Two examples

1.Tom
2.Ayrn


![Annotation 2023-08-06 175403](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/0b998369-c93e-4fae-90cd-3269223d8850)

Configure [Users(customers)] 

Users (customers) accounts can be created and log in to create a ticket and check on their status.

Agent Panel---->Users--->Add New

1.Kat
2.Ron

![Annotation 2023-08-06 180047](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/799a6d91-e9e1-491a-965d-adea1df62d83)


Configure[SLA]

SLA Plans or Service Level Agreements, these are unlimited in osTicket. This aloows are time length which a ticket must be completed or "closed"
Admin Panel---->Manage---->SLA

1.Sev-A (1 hour, 24/7)
2.Sev-B (4 hours, 24/7)
3.Sev-C (8 hours, business hours)

![Annotation 2023-08-06 180928](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/02615cbe-2792-406a-898f-8b4db49129a0)


Configure [Help Topics]

Help Topics will keep end-user's help desk experience proper assignment and prompt response to the tickets. [Create as many Help Topics as needed]. 
Admin Panel--->Manage---->Help Topics

-Business Critical Outage
-Personal Computer Issues
-Equipment Request
-Password Reset


![Annotation 2023-08-06 181424](https://github.com/Leibwatcher/Post-Install-Configuration/assets/137578446/9af3cd30-8ef7-448c-b778-0ef9133e9efe)

</p>
<br />


</p>
<p>

</p>
<br />
