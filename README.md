<p align="center">
<img src="https://i.imgur.com/tUnlhRz.jpeg" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>osTicket: Post-Installation Configuration</h1>

<h2>Description</h2>
This project focuses on configuring osTicket, so it can be used properly as a ticketing system. It consists of setting up multiple agents along with their departments, roles, and permissions. As well as, configuring SLAs (Service Level Agreements), help topics, and users.<br/>
<br/>

<br />


<h2>Environments and Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Virtual Machines</b>
- <b>Remote Desktop Connection</b>
- <b>osTicket</b>


<h2>Operating Systems Used </h2>

- <b>Windows 10</b>

<h2>Project Walk-through:</h2>

<p align="center">
With osTicket open navigate to the Admin Panel by clicking "Admin Panel" located in orange at the top right of the page: <br/>
<img src="https://i.imgur.com/AtfsyHt.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To start configuring Roles Navigate to the "Agents" tab and click on "Roles" underneath the "Agents" tab. Enter a role name:  <br/>
<img src="https://i.imgur.com/MN6UfEk.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
In the "Permissions" tab of this role, give this role all permissions in "Tickets", "Tasks", and "Knowledgebase". This will be our "Supreme Admin" Role:  <br/>
<img src="https://i.imgur.com/Mv4zvR1.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To set up departments, while still in the "Agents" tab, click on "Departments" located just below the "Agents" tab. Name the department "System Administrators" and create the Department:  <br/>
<img src="https://i.imgur.com/hOIJf2p.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next, create a team by selecting the "Teams" tab, while still in the "Agents" tab. Then, name the team "Level II Support" and create team:  <br/>
<img src="https://i.imgur.com/24nfzxl.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now, to allow anyone to create tickets, go to the "Settings" Tab, and under "Authentication Settings" make sure that "Require registration and login to create tickets" is unchecked:  <br/>
<img src="https://i.imgur.com/AyStvna.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To create agents (the help desk workers) navigate back to the "Agents" tab and select "Agents" and fill out the name, email, and username:  <br/>
<img src="https://i.imgur.com/4wELAv7.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next to the username click "Set Password" set the password. Uncheck the "Send the agent a password reset email" and "Require password change at next login" options:  <br/>
<img src="https://i.imgur.com/Nz0uObT.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
On the "Access" tab for this user select the "System Administrators" department and the "Supreme Admin" role created earlier:  <br/>
<img src="https://i.imgur.com/6gUyzMx.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Under the "Teams" tab select "Level II Support" for this agent:  <br/>
<img src="https://i.imgur.com/ys2Mzey.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Create one more agent as done previously, the only difference is in the "Access" tab select "Support" for the department:  <br/>
<img src="https://i.imgur.com/NVBIhkr.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/PfgX4Yj.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next, to create a user (the customers) switch to the "Agent Panel" in orange in the top right> Users> Add User and put an email and name, then create. (I also made one more user with the same steps taken here):  <br/>
<img src="https://i.imgur.com/RlkBrtu.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Configuring an SLA plan navigate back to Admin Panel> Manage> SLA create three SLAs with different severities, grace periods, and schedules like so:  <br/>
<img src="https://i.imgur.com/MiAcErr.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/8RuBEXi.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/vJuJwqJ.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Under the same "Manage" tab go to the "Help Topics" tab and create four help topics named, "Business Critical Outage", "Personal Computer Issues", "Equipment Request", and "Password Reset" all with the same settings like so:  <br/>
<img src="https://i.imgur.com/PpoOpZE.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />


<h2>osTicket Setup Complete!</h2>

<b> We've successfully set up multiple agents along with their departments, roles, and permissions. As well as, configured SLAs (Service Level Agreements), help topics, and users! osTicket is now setup for the next project where I will create and work different tickets using multiple agents and users!  </b>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
