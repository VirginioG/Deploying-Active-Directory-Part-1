<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Deploying-Active-Directory-Part-1</h1>
This tutorial guides you through setting up a Domain Controller (DC) using Active Directory Domain Services (AD DS) in a Windows Server environment. It covers creating organizational units (OUs), establishing a domain admin user, and joining a client machine (Client-1) to the domain. Finally, the tutorial helps you organize and manage domain users and computers within Active Directory for better administration. <br />


<h2>Video Demonstration</h2>

- ### [Deploying-Active-Directory-Part-1](https://youtu.be/kdiHus6eiRc?si=aAm-g_4NeCuBEfsZ)

<h2>Environments and Technologies Used</h2>

-Microsoft Azure (Virtual Machines/Computer)

-Remote Desktop

-Active Directory Domain Services

-Active Directory Users and Computers


<h2>Operating Systems Used </h2>

-Windows Server 2022

-Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Log into DC-1, install Active Directory Domain Services, and promote it as a Domain Controller with a new forest (e.g., mydomain.com). After a restart, log back in as mydomain.com\labuser.
- In Active Directory Users and Computers (ADUC), create OUs _EMPLOYEES and _ADMINS. Create a user jane_admin with password Cyberlab123!, add them to the Domain Admins group, and then log out. Log back in as mydomain.com\jane_admin and use this account as the admin moving forward.
- Set Client-1's DNS to DC-1’s private IP (already done), restart Client-1, and log in as the local admin (labuser). Join Client-1 to the domain, restart, and verify it shows up in ADUC. Create an OU _CLIENTS and move Client-1 into it.

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
