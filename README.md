<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial, I will walk through the post-installation configuration of osTicket, an open-source help desk ticketing system designed to optimize customer support processes. Also I will demonstrate how to create users, agents, and more.
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
We're going to kick this off by configuring Roles. A role is a permission that grants agents access.To configure roles, navigate to the Admin Panel → Agents → Roles, where you can manage agents available access. Next, we move on to Departments. A department helps determine ticket visibility. For example, if someone in the Accounting department has a computer issue and needs tech support, they can simply refer to the Accounting Department when creating a ticket. This makes it easier for the agent to identify and handle the issue promptly. In the Departments section of the Admin Panel, tickets can be assigned to different departments. You can find this option by going to Admin Panel → Agents → Departments. Teams are used to group individuals from different departments, allowing them to collaborate on tasks. Within a team, members can have varying roles and permissions. To configure Teams, navigate to Admin Panel → Agents → Teams. Next, we’ll configure a setting that allows users to create tickets without requiring them to log in. This can be done by going to Admin Panel → Settings → User Settings and unchecking the option for Registration Required. Finally, we’ll create an account for agents (workers). To do this, go to Admin Panel → Agents → Add New. An SLA(Service Level Agreement) is the amount of time an agent has to resolve or respond to a ticket. To configure SLA, go to Admin Panel → Manage → SLA → Add New SLA. The final thing to configure is a Help Topic, which is the category selected by the user submitting the ticket or the agent resolving the issue. To confiure this we go to Admin Panel → Manage → Help Topics → Add new Help Topics.

<br />


<h3>Example how to create a Help Topic:</h3>
<p>To create a Help Topic: Admin Panel → Manage → Help Topics → Add new Help Topics</p>

<img src="New Help Topic.jpg" height="25%" width="25%" alt="Help Topic" />

<p>Once reached the "Add New Help Topic" page, fill out all the required fields. For this exmaple I'll use the following:</p>
<p>Topic: Computer Issue</p>
<p>Status: Active</p>
<p>Type: Public</p>
<p>Parent Topic: Report a Problem</p>

<p>Then click 'Add Topic' and it will be successfully added.</p>

<p>Follow the same steps to create 3-4 topics to use it for a practice in the Ticket Lifecycle. https://github.com/united16/ticket-lifecycle</p>


<h3>Example how to create a user:</h3>

<p>To create a user/customer, I'll login as an Admin and navigate to Admin Panel → Users → Add new</p>

<p><img src="New user.jpg" height="15%" width="15%" alt="New user" /></p>

<p>Once getting to the page, fill out all the required fields. For this exmaple I'll use the following: </p>
<p>Email-Address: oror@hotmail.com</p>
<p>Full Name: Wayne Roro</p>

<p>Then click 'Add User' and it will successfully create</p>


<h3>Example how to create an Agent:</h3>

<p>To create an Agent, I'll login as an Admin and navigate to Admin Panel → Agents → Add New Agent</p>

<p><img src="New user.jpg" height="15%" width="15%" alt="New user" /></p>

<p>Once getting to the page, fill out all the required fields. For this exmaple I'll use the following: </p>
<p>Email-Address: jt16@yahoo.com</p>
<p>Full Name: Jack Tommy</p>
<p>Username: jt16 (click 'Set Password' to the right of username and uncheck the option to send a password reset email)+
</p>
<p>Assign the agent a department and role</p>

<p>Then click 'Create' and it will successfully create the Agent</p>
















<!-- <h2>Creating Role, Department, Teams and Users</h2>

<h4>Roles<h4/> 
 <br />
  
<p>
Enter login information and click the 'Login' button
</p>

<img src="Roles/Credentials .jpg" height="15%" width="15%" alt="Credentials"/>
<br /> <br />

Admin Panel 
<p>
  Then click 'Admin Panel'(circled in blue)
</p>
<img src="Roles/Panel.jpg" height="15%" width="15%" alt="Admin Panel"/>
<br /> <br />

Agents  
<p>
 Next, hover the cursor over 'Agents' and click on 'Roles'
</p>
<img src="Roles/Cursor.jpg" height="15%" width="15%" alt="Cursor"/>
<br /> <br />

Roles 
<p>
 Once on the Roles page, click 'Add New Role'
</p>

<img src="Roles/Adding.jpg" height="15%" width="15%" alt="Adding"/>
<br /> <br />

Naming
<p>
 Give the new role a name
</p>
<img src="Roles/Naming.jpg" height="15%" width="15%" alt="Naming"/>
<br /> <br />

Permission
<p>
After naming the role, go to the 'Permissions' section (to the right of 'Definition') and assign either full access or minimum access, depending on the level of access you want to grant.Then, click the 'Add Role' button at the bottom to create the role.
</p>
<img src="Roles/Permiss.jpg" height="15%" width="15%" alt="Permissions"/>
<br /> <br />

Success
<p>
Role has been created and will appear at the top of the list. You can click on it to modify the permissions or change the name
</p>
<img src="Roles/Success.jpg" height="15%" width="15%" alt="Success"/>
<br /> <br /> 


<h3>Department</h3> <br />

Admin Panel
<p>
 Click on 'Admin Panel'(circled in blue)
</p>
<img src="Roles/Panel.jpg" height="15%" width="15%" alt= "Panel"/>
<br /> <br />

Agents
<p>
Hover the cursor over "Agents," then click on Department.
</p>
<img src="" height="15%" width="15%" alt="Agent"/>
<br /> <br />



Before beginning the configuration process,locate the link(highlited in red) to direct you to the Admin or Control pannel to log in with the Admin account that was created in the Admin User section.
<img src="" height="25%" width="25%" alt=""/> 

<p>
</p>
<img src="" height="15%" width="15%" alt=""/>
<br /> <br />


-->
