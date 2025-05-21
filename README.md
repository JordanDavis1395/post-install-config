<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
Here’s a tutorial on how to configure roles, departments, teams, users, agents, SLAs, and help topics in osTicket:<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Follow this complete [osTicket Installation Tutorial](https://github.com/JohnSomanza/osTicket-Prereqs.git) before starting this tutorial

<h2>Configuration Steps</h2>

<p> Before proceeding, head over to `localhost/osTicket/scp/login.php` in your VM's browser and log in using the admin account you created during the osTicket installation tutorial.</p>
<img src="https://i.gyazo.com/255cf2560f9907342d99cb6fb5120444.png">
<p>Step 1 Configure Roles: Go to the Admin Panel -> Click on Agents -> Select Roles -> Create a new role called "Supreme Admin"</p>
<img src="https://i.gyazo.com/6656e33d64730ea9a6fbd0da26bf53b3.png">
<img src="https://i.imgur.com/OxqJqpi.png">
<img src="https://i.imgur.com/1u3meGQ.png">
<img src="https://i.gyazo.com/f423597ac97416b59d601cbac6d10523.png">
<img src="https://i.gyazo.com/e967c85ed942a62d58b15465e78820b6.png">
<img src="https://i.gyazo.com/6d870d55c1e56616297eacef1688d656.png">
<img src="https://i.gyazo.com/faad144ad4e02df4a71b82592b1d9e7e.png">
<img src="https://i.gyazo.com/faad144ad4e02df4a71b82592b1d9e7e.png">
</p>
<p>Step 2 Configure Departments: Go to the Admin Panel -> Click on Agents Select Departments -> Create a new department called "System Administrators"</p>
<img src="https://i.imgur.com/jMBjqzF.png">
<img src="https://i.imgur.com/3SM9cRZ.png">
<img src="https://i.imgur.com/pONS6GQ.png">
<img src="https://i.gyazo.com/93d01bcb04f16589fe562e0415fef781.png">
<p>Step 3 Configure Teams: Go to the Admin Panel -> Click on Agents -> Select Teams -> Create a new team: "Level II Support"</p>
<img src="https://i.imgur.com/zYvAh3x.png">
<img src="https://i.imgur.com/DbzrGQ2.png">
<img src="https://i.imgur.com/HCQtn0o.png">
<p>Step 4 Configure Agents (workers): Go to the Admin Panel -> Click on Agents -> Select Add New -> Add two new agents: Jane and John</p>
<img src="https://i.imgur.com/k4DcSbo.png">
<img src="https://i.imgur.com/XR1ixR9.png">
<img src="https://i.gyazo.com/b3223f6647282b6328edbba31806b506.png">
<img src="https://i.imgur.com/czijxly.png">
<img src="https://i.imgur.com/emHaH3D.png">
<img src="https://i.gyazo.com/5edb69d58d80ab26b0b561969a0b42af.png">
<img src="https://i.imgur.com/7S50hjT.png">
<p>Step 5 Configure Users (customers): Go to the Agent Panel -> Click on Users -> Select Add New -> Add two new users: Karen and Ken</p>
<img src="https://i.imgur.com/TVjOotN.png">
<img src="https://i.imgur.com/d9oWh9c.png">
<img src="https://i.gyazo.com/f6565a4e402005c59e7bad4c2d0f08e6.png">
<img src="https://i.imgur.com/kmIIlet.png">
<img src="https://i.gyazo.com/3043e340379017a50b97295719c5e7f3.png">
<p>Step 6 Configure SLA: Go to the Admin Panel -> Click on Manage -> Select SLA -> Create three new SLAs: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours)</p>
<img src="https://i.imgur.com/1YX8GSX.png">
<img src="https://i.imgur.com/ptedwOe.png">
<img src="https://i.imgur.com/XOiZ1qx.png">
<img src="https://i.imgur.com/rIZJkrg.png">
<p>Step 7 Configure SLA: Go to the Admin Panel -> Click on Manage -> Select Help Topics -> Create four new help topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset</p>
<img src="https://i.imgur.com/rBSXxhk.png">
<img src="https://i.imgur.com/Mr3E0Bl.png">
<img src="https://i.imgur.com/avOxSSS.png">
<img src="https://i.imgur.com/HqcIpQD.png">
<img src="https://i.imgur.com/Ak8Yit7.png">
<p>Fin! You've successfully configured roles, departments, teams, users, agents, SLAs, and help topics in osTicket..</p>
