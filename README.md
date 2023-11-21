<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<!--
<h2>Video Demonstration</h2>
--
- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)
-->
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments and Teams
- Allow anyone to create tickets
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%"/>
</p>
<p>
Configure Roles<br>
Admin Panel -> Agents -> Roles<br>
Supreme Admin<br><br>
Configure Departments<br>
Admin Panel -> Agents -> Departments<br>
System Administrators<br><br>
Configure Teams<br>
Admin Panel -> Agents -> Teams<br>
Level I Support<br>
Level II Support<br>

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%"/>
</p>
<p>
Allow anyone to create tickets<br>
-Admin Panel -> Settings -> User Settings<br>
-Registration Required: Require registration and login to create tickets 

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%"/>
</p>
<p>
Configure Agents (workers)<br>
Admin Panel -> Agents -> Add New<br>
-Jane<br>
-John<br><br>
Configure Users (customers)<br>
Agent Panel -> Users -> Add New<br>
-Karen<br>
-Ken

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%"/>
</p>
<p>
Configure SLA<br>
Admin Panel -> Manage -> SLA<br>
-Sev-A (1 hour, 24/7)<br>
-Sev-B (4 hours, 24/7)<br>
-Sev-C (8 hours, business hours)

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%"/>
</p>
<p>
Configure Help Topics<br>
Admin Panel -> Manage -> Help Topics<br>
-Business Critical Outage<br>
-Personal Computer Issues<br>
-Equipment Request<br>
-Password Reset

<br />
