<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create a new role <b>Supreme Admin</b> with all permissions
- Create a new department <b>System Administrators</b>
- Create a new team <b>Level II Support</b>
- Allow anyone to create tickets
- Create new agents <b>Jane Doe</b> and <b>John Doe</b>
- Configure new SLA plans <b>SEV-A</b>, <b>SEV-B</b>, and <b>SEV-C</b>
- Add new Help Topics <b>Business Critcal Outage</b>, <b>Personal Computer Issues</b>, <b>Equipment Request</b>, and <b>Password Reset</b>

<h2>Configuration Steps</h2>

<p>
<b>1.) Login as admin in the Help Desk login page</b> (http://localhost/osTicket/scp/login.php)

- username: johnan
- password: Passpassword1
<p>
<img src="https://i.imgur.com/fcg88Xb.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<b>2.) Configure Roles</b>

- Navigate to Admin Panel -> Agents -> Roles
- Create a new role:   <b>Supreme Admin</b>
- Assign all permissions under <b>Tickets</b>, <b>Task</b>, and <b>Knowledgebase</b> tabs
</p>

<p>
<img src="https://i.imgur.com/0QR8TiK.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/JDbadqy.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Ns37Wjn.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/klC91Ic.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
<b>3.) Configure Departments</b>
   
- Navigate to Admin Panel -> Agents -> Departments</b>  
- Create a new department: <b>System Administrators</b>
</p>
<p>
<img src="https://i.imgur.com/5JQvKeP.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
<b>4.) Configure Teams</b>
   
- Navigate to Admin Panel -> Agents -> Teams</b>
- Create a new team: <b>Level II Support</b>
</p>
<p>
<img src="https://i.imgur.com/A0tqVbm.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
<b>5.) Allow anyone to create tickets</b>
   
- Navigate to Admin Panel -> Settings -> User Settings
- <b>Under Registration Required</b>, uncheck <b>Require registration and login to create tickets</b>
</p>
<p>
<img src="https://i.imgur.com/NkeUfCU.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>6.) Configure Agents (workers)</b>

- Navigate to Admin Panel -> Agents -> Add New
- Create agents:
   - <b>Jane Doe</b> with <b>System Administrators</b> and <b>Supreme Admin</b> (department, role)
   - <b>John Doe</b> with <b>Support</b> and <b>View Only</b> (department, role)
- Set password for both agents: <b>Password1</b>
</p>
<p>
<img src="https://i.imgur.com/ItnABQm.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/a932UW5.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
<b>7.) Configure Users (customers)</b>
   
- Navigate to Agent Panel -> Users -> Add New
- Create Users:
   - <b>Karen</b>
   - <b>Ken</b>
</p>
<p>
<img src="https://i.imgur.com/buHQsHw.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/uo3neHV.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
<b>8.) Configure SLA</b>
   
- Navigate to Admin Panel -> Manage -> Add New SLA Plan
- Configure SLA categories:
   - <b>Sev-A</b> (1 hour, 24/7)
   - <b>Sev-B</b> (4 hours, 24/7)
   - <b>Sev-C</b> (8 hours, business hours)
</p>
<p>
<img src="https://i.imgur.com/TIn37WS.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Nt7XPgQ.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
<b>9.) Configure Help Topics</b>
   
- Navigate to Admin Panel -> Manage -> Add New Help Topics
- Configure <b>Help Topics</b>:
   - Business Critical Outage
   - Personal Computer Issues
   - Equipment Request
   - Password Reset
</p>
<p>
<img src="https://i.imgur.com/qgxW2h2.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ze9qjxq.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>





