
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This lab demonstration covers the necessary requirements and step by step installation process for osTicket, and open source desk ticketing system.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure roles
- Configure teams and Departments
- Allow anyone to create tickets
- Configure agents
- Configure users
- Configure SLA
- Configure Help Topics
  
<h2>Configuration Steps</h2>
<p>
After installing osTicket, it's time to set it up as a ticketing system. Note that you'll switch between Admin and Agent, panels, each wtih different settings. To see which panel you're using,check the top right of the osTickets screen. If it says "Agent Panel," you're in the Admin panel,and vice versa.
</p>
<br />
<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/b8dc4964-e3e3-42d4-bffa-afec84073b2c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/10d02131-0c54-4117-a744-9aa33f12919c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/98ba854f-50fa-4b83-9a17-fe9b47ae8fd0" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>






1.To start, create a new role called "Supreme Admin." In the Admin panel, go to the Agents Menu, click on Roles, and then create the new role from there. This role will have all possible permissions for the purpose of this lab. 
</p>
<br />

<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/abb2bef0-1d56-436f-81ae-d08e862efcd4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2.Next, lets create a new Department specifically for Systems Administrators. Go to the Admin panel, navigate to the Agents menu, and click on Departments to set up the new Department in osTicket. 
</p>
<br />



   <p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/303878a5-b1c2-454e-ab50-91ea27c704ba" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
3.To expand on the existing Level I Support Team in osTicket, create a new level II Support Team. Access the Admin panel, navigate to the Agent menu, and select Teams. From there, add any additional teams that are needed. 
</p>
<br />




<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/4b1e1f56-509b-4e1d-80f5-c61b2f26fb23" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/59231a2b-c37b-4b4b-a7c2-ff9cf06d7bdc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
4. To ensure smooth handling of incoming tickets, both new agents and users need to be added to osTicket. 
  
  Add New Agents,and go to Agent menu. Select "Add New Agent" to create account credentails for each agent. For this Demonstration, Jane Doe will be created. 

  To add New User navigate to the agents panel and open the users menu. Click on Add User to set up account credentials for each new user. 
</p>
<br />
<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/3cb85e1a-dd5d-41ca-8506-377c1f173be2" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/259dd39a-ae6d-4a9a-94aa-c51f8f8df8cb" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

5.To sort out tickets by thier impact levels, you need to set up Service Level Agreements (SLAs). Navagate to the Admin panel and click on Manage menu. Select SLA to create new ones. Create SEV-A,B,and C to prioritze tickets that need to be responded within 1 hour,all day, withen 4 hours, all day, and withen 8 hours, during business hours. 
</p>
<br />
<p>
<img src="https://github.com/CynthiaBrady/post-install--configuration/assets/160746865/3cf17cdb-7f02-4915-8c29-175a970584d7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


6.To help users choose the correct category for thier issues and help agents understand ticket problems better, we need to create Help Topics. Go to the Admin panel, then click topics like Business Critical Outrage, Personal Computer Issues,Equipment Request, and Password Reset for future ticket creation. 
</p>
<br />



