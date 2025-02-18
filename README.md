
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
This lab demonstrates the necessary changes I make to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)


<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/1e1119ae-8d7d-41e7-a8d5-e01c35253794)

<p>
After installing osTicket, it is now time to make configurations to use it as a ticketing system. One thing to note is that I switch between Admin and Agent panels as each panel has different configurations. To tell which panel is used, look at the top right of the osTicket screen. If it reads Agent Panel, the Admin panel is the one being used and vice versa.

The first step to take is to make a new role called Supreme Admin. For the purposes of this lab, I am intentionally creating a role that has every permission that can be granted. To create a new role, open the Admin panel enter the Agents Menu. Click on Roles and create the new role from there.
</p>
<br />

![image](https://github.com/user-attachments/assets/ea9953a6-e933-43e8-b7ba-282918041235)

<p>
Next, a new Department will be created for System Administrators. In the Admin panel, open the Agents menu and click on Departments to create a new Department within osTicket.
</p>
<br />

![image](https://github.com/user-attachments/assets/73dda71d-dc55-4beb-b22b-e55b55202aff)

<p>
Next, we will create a new team. To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add any new teams that need to be created.
</p>
<br />

![image](https://github.com/user-attachments/assets/04dd81ff-0654-4061-a6d3-357a656efcc6)


![image](https://github.com/user-attachments/assets/fd47646f-5bdd-4bbd-a6f8-c4f2cd3679c5)


New agents will have to be created so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent. In this case, Jane and John Doe are created.
</p>
<br />

![image](https://github.com/user-attachments/assets/6a2b69e8-daa0-4d77-98f8-f505651970bd)

New users will be created so they can create tickets so that the agents can receive and triage them. To create new users, enter the Agents panel and open the Users menu. Click on Add User and create the account credentials necessary for each new user. In this case, Karen and Ken have been created.
</p>
<br />

![image](https://github.com/user-attachments/assets/44a6d69f-0030-498f-a0e7-a9e14b709d7c)

<p>
Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact. To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively.
</p>
<br />

![image](https://github.com/user-attachments/assets/aa8557bf-5573-48f6-a41a-822e78dae421)

<p>
Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, I have added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>
<br />

<h2>osTicket Configurations are Complete </h2>

Now that the configurations have been set in place, I can now utilize osTicket as a proper ticketing system. I can create tickets and be able to traige them as if I were in a real environment.
