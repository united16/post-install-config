<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial, I'll demonstrate the post-installation configuration of osTicket, an open-source help desk ticketing system designed to optimize customer support processes.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2) <br />


<h2>Configuration Steps</h2>

<h4>Log-in</h4>
<p>
<img src="link.jpg" height="25%" width="25%" alt="Link"/> <img src="Credentials.jpg" height="20%" width="20%" alt="Credentials"/> 
</p>
<p>
Before starting the configuration process, locate the link (highlighted in red) that directs you to the Admin or Control Panel. Use this link to log in with the Admin account created in the Admin User section. And to access the end user accounts, use the link on the left (highlighted in blue).
</p>
<br />

<h4>Configuring</h4>

<p>
We're going to kick this off by configuring Roles. A role is a permission that grants agents access.To configure roles, navigate to the Admin Panel → Agents → Roles, where you can manage agents available access. Next, we move on to Departments. A department helps determine ticket visibility. For example, if someone in the Accounting department has a computer issue and needs tech support, they can simply refer to the Accounting Department when creating a ticket. This makes it easier for the agent to identify and handle the issue promptly. In the Departments section of the Admin Panel, tickets can be assigned to different departments. You can find this option by going to Admin Panel → Agents → Departments. Teams are used to group individuals from different departments, allowing them to collaborate on tasks. Within a team, members can have varying roles and permissions. To configure Teams, navigate to Admin Panel → Agents → Teams. Next, we’ll configure a setting that allows users to create tickets without requiring them to log in. This can be done by going to Admin Panel → Settings → User Settings and unchecking the option for Registration Required. Finally, we’ll create an account for agents (workers). To do this, go to Admin Panel → Agents → Add New.
<br />

<h2>Creating a Role, Department, Teams and Users</h2>

<h4>Roles<h4/> 
<p>
  Admin Panel → Agents → Roles 
  <br />
  
<img src="" height="25%" width="25%" alt=""/>
 
</p>
<br />

<h4>Department<h4/>
<p>

 
</p>
<br />

<h4>Teams<h4/>
<p>

 
</p>
<br />

<h4>Users<h4/>
  <p>

 
</p>
<br />
<!--Before beginning the configuration process,locate the link(highlited in red) to direct you to the Admin or Control pannel to log in with the Admin account that was created in the Admin User section.
<img src="" height="25%" width="25%" alt=""/> -->
