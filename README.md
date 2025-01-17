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
We're going to kick this off by configuring Roles. A role is a permission that grants agents access.To configure roles, navigate to the Admin Panel → Agents → Roles, where you can manage the available access. Next, we move on to Departments. A department helps determine ticket visibility. For example, if someone in the Accounting department has a computer issue and needs tech support, they can simply refer to the Accounting Department when creating a ticket. This makes it easier for the agent to identify and handle the issue promptly. In the Departments section of the Admin Panel, tickets can be assigned to different departments. You can find this option by going to Admin Panel → Agents → Departments. Teams is used to group people from diffrent departments and in that group people may have diffrent tasks or permissions. We can configure Teams by going to Admin Panel → Agents → Teams. Next we'll configure a setting that lets users create ticket without them logining in. That can be done by going to Admin Panel → Settings → User Settings → Uncheck: Registration Required. Next we'll create an account for Agents(workers). We can locate that by going to: Admin Panel → Agents → Add New. 

<br />

<h4>Creating a Role, Department, Teams, and Users</h4>

<p>
<img src="" height="25%" width="25%" alt=""/>
</p>
<p>

</p>
<br />



<!--Before beginning the configuration process,locate the link(highlited in red) to direct you to the Admin or Control pannel to log in with the Admin account that was created in the Admin User section.-->
