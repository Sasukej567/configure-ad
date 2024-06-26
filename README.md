<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Ensure connectivity between the client and Domain Controller. 
- Install Active Directory.
- Create an Admin and Normal User Account in AD (Active Directory). 
- Then join Client to your domain (mydomain.com).
- Setup Remote Desktop for non-administrative users on Client.
- Create a bunch of users and attempt to log into Client with one of the users.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/iJrxxdJ.png" height="80%" width="80%" alt="Checking connectivity"/>
</p>
<p>
Connectivity between the Client and Domain Controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/50ZXxJS.png" height="80%" width="80%" alt="Install Active Directory."/>
</p>
<p>
Install Active Directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/LM0x8mU.png" height="80%" width="80%" alt="Client joined domain"/>
</p>
<p>
Client joined to Domain.
</p>
<br />

<p>
<img src="https://i.imgur.com/d74taYm.png" height="80%" width="80%" alt="Users created"/>
</p>
<p>
Users created and ready to login to Client.
</p>
<br />
