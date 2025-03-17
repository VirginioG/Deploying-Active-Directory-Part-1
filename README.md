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


![Part2Part1](https://github.com/user-attachments/assets/aa1eed8d-4440-4939-84a5-0983af61fcbe)



</p>
<p>
Access the DC-1 server.

Open Server Manager > Manage > Add Roles and Features.

Choose Role-based or feature-based installation, then select Active Directory Domain Services.

Follow the prompts to install AD DS.

After installation, open Server Manager, and click on the Notification Flag.

Select Promote this server to a domain controller.

Choose Add a new forest and name it mydomain.com (or any other domain name you prefer).

Set up Directory Services Restore Mode (DSRM) password and complete the wizard.

Restart the server when prompted.

After the restart, log into DC-1 as mydomain.com\labuser.


</p>
<br />

<p>


![Part2Part2](https://github.com/user-attachments/assets/21b3ca29-588d-44f3-9d2f-4edc9b255060)



</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>


![Part2Part3](https://github.com/user-attachments/assets/fb10ec4f-3fc4-42db-83cf-44decf0c4e50)



</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
