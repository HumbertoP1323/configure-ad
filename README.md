<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<b 





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- create  virtual machines in Azure
- install active directory 
- Establish both an administrative and a regular user account within Active Directory.


<h2>Deployment and Configuration Steps</h2>

<p><img src="https://i.imgur.com/3kOUMl1.png" width="80%" alt="Create Virtual Machines"/>
</p>
<p>
 It's necessary to generate a pair of virtual machines. The initial virtual machine will utilize Windows 10, while the second will operate under the Windows Server environment.
</p>
<br />

<p>
<img src="https://i.imgur.com/CzW7ZoM.png" height="80%" width="80%" alt="Install Active Directory"/>
</p>
</p>
<p>
Utilize your remote desktop connection to the virtual machine to access the server manager and install Active Directory, configuring necessary settings for a functional environment. Upon completion, you'll have a fully operational Active Directory instance.
</p>
<br />

<p>
<img src="https://i.imgur.com/CgXnzt2.png" height="80%" width="80%" alt=" Create Admin and Normal User Account in AD"/>
</p>
<p>
Create a user account in the admin folder and adjust the properties to set it as an admin. Repeat this process for the user account in the employee folder.
</p>
<br />
