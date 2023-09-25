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
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (Customers)
- Configure SLA

<h2>Configuration Steps</h2>


![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/1a07e229-64ea-4bc5-ba38-68cfd3e088ce)



Step 1: Using OSticket, navigate to the admin Panel, then agents, and then roles. Enable a supreme admin by checking all the permissions.
</p>
<br />

![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/f56fa567-a01c-4711-b750-313f6a6c1874)




Step 2: Navigate to departments, going through the admin panel in os ticket, click agents, then departments. Click create new department and create a department called System administrators.
</p>
<br />

![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/f1e44a5b-4caa-4559-b014-e477d1e94f2e)

Step 3: Go into Admin panel, under agents, then navigate to teams. Create two teams, one named "level 1 support" and the other "level 2 support".

![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/98e2fd80-c3ff-4362-a817-96a44df8157e)

Step 4: This step will allow anyone to create tickets. In the admin panel, go to settings, then user settings, make sure that the "registration required: Require registration login to create tickets" is unchecked.
</p>
<br />









![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/e818207d-862f-49b7-93f5-a693453b8c5a)

Step 5: In the admin panel, under agents click "add new", hear you can create new agents to use osticket to troubleshoot problems that are received via ticket.
</p>
<br />

![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/35da4059-3fe5-4b08-b99d-a61e982be490)

Step 6: In the Agent Panel, under user click "add new", this gives you the ability to create new users.
</p>
<br />

![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/dbdf2cef-9052-48ee-8ef4-90039a973ee1)

Step 7: SLA stands for "service level agreement", this is defined as a contract between a service provider and a customer. In the admin panel, under manage click "SLA", here you can create new SLA's and adjust specific details of each SLA such as total time to complete.
</p>
<br />

![image](https://github.com/JaMyraJones/post-install-config/assets/145633544/ed15ebe9-1127-4a69-9d81-87509663db4e)

Step 8: In the admin panel, under manage click "help topics", here you can add help topics such as "personal computer issues" or "password reset", in order to allow users to help themselves.
</p>
<br />
