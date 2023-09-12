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

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/Bvk39iF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/ITAXLtY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Since osTicket has been installed now it is time to make configurations to be able to use the ticketing system. During the lab I switch between Admin and Agent panels because they have different configurations.
</p>
<br />

<p>
<img src="https://i.imgur.com/TH7RUgH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First make a new role called Supreme Admin and giving it every permission for the purpose of this lab. To create a new role open Admin panel and enter the agents menu. Click on Roles and create the new role.
</p>
<br />

<p>
<img src="https://i.imgur.com/L2OlkyQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next is to create a new Department for System Administrators. In the Admin panel, open the Agents menu and click on Departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/VsZL72c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next create a new Level II Support Team to supplement the Level I Support thats already made on osTicket. Create a new Team by entering the Admin panel and open the Agents menu. Click on Teams and add the new Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/B3HSVI5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next create new Agents so they can take tickets that come in. To create new agents, enter the Admin panel and open the Agetns menu. Click on Add New Agent and create the account credentials for each new agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/WGXOd2u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now new users will be created to begin creating tickets for our new agents. To create new users enter the agents panel and open Users menu. Click on Add user and create the account credentials for each user.
</p>
<br />

<p>
<img src="https://i.imgur.com/XOudYDA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now Service Level Agreements (SLAs) will need to be made in order to categorize tickets according to their level of impact and urgency. To make SLAs enter the Admin panel and open the Manage menu. Click on SLA and create. For example SEV-A, B, and C will categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours.
</p>
<br />

<p>
<img src="https://i.imgur.com/EsTVkx0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, Help Topics need to be created to help users select an appropriate category for their problem. This allows the agents to have an idea of what the problem is for the end user. Enter the Admin panel and open the Manage menu. Click on Help Topics and Add New Help Topic. For example Buisness Critical Outage, Personal Computer Issues, Euipment Reset, and Passowrd Request can help organize problems for the users.
</p>
<br />

<h1>osTicket Configurations are Complete!</h1>

<p>
Now the osTicket can be utilized as a proper ticketing system. Tickets can now be created and resolved in the system. 
</p>
