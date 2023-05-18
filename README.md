<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets (default)
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/PxESC6Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a "Supreme Admin" role that has permissions to do everything.
</p>
<br />

<p>
<img src="https://imgur.com/2PB38tp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a "System Administrators" department with default settings.
</p>
<br />

<p>
<img src="https://imgur.com/xG08erV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a "Level II Support" team with default settings.
</p>
<br />

<p>
<img src="https://imgur.com/m2Bakru.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created two agents called "Jane Doe" and "John Doe," which are the actual help desk professionals.
</p>
<br />

<p>
<img src="https://imgur.com/NEMRVgg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created two users called "Karen Karson" and "Ken Karson," which are the customers who create the help tickets.
</p>
<br />

<p>
<img src="https://imgur.com/9IJqKAr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created three SLA plans called "Sev-A," "Sev-B," and Sev-C." They have different grace periods and schedules depeneding on the severity.
</p>
<br />

<p>
<img src="https://imgur.com/YB0oTc9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created four help topics called "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset." These help streamline end-user's help desk experience because they ensure a proper assignment and a prompt response to a ticket.
</p>
<br />
