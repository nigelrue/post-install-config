<p align="center">
<img src="https://static.wixstatic.com/shapes/2ebf04_6ddec2f2c2eb4cd4ada9cef3f6ace924.svg" alt="osTicket Logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial provides a comprehensive guide to the post-installation configuration procedures of the open-source help desk ticketing system, osTicket. Users can learn how to optimize their osTicket installation by configuring its various admin/agent settings, including roles, departments, ticket templates, and more.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Establish a senior administrator position with appropriate role-based access control privileges and permissions.
- Implement a new department for system administrators.
- Configure one team responsible for level II support issues.
- Create three agents with distinct roles and permissions based on their job requirements.
- Add two users who will serve as example customers by sending in support tickets.
- Configure service-level agreements (SLAs) by establishing performance metrics and customer service targets.
- Set up four help topics that enable customers to easily narrow down their support issues.

<h2>Configuration Steps</h2>
<p align="left"> Part 1: <a href="https://github.com/nigelrue/osticket-prereqs">osTicket: Prerequisites and Installation</a></p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/q75JHHZP/temp-Image4-UFe6-W.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://i.postimg.cc/Kz6RbR5T/temp-Imagevbz-Zm7.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://i.postimg.cc/qMf3VZmF/temp-Imagelk0ol-T.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center">
<img src="https://i.postimg.cc/gcLZ7PKR/temp-Image-G6-S2-E1.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 1: Navigate to the admin panel, then click on Agents, followed by Roles, and select the option to add new roles.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/9QbR9XW3/temp-Imageqxk-J96.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 2: Use "Supreme Admin" as the name for the new role.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/wBb1WWy0/temp-Imagebk-KAij.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/wThs6cZj/temp-Image-Q2k-MLk.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 3: Check all the permissions under the Tickets, Tasks, and Knowledgebase tabs, and select "Add Role."
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/433KQCdY/temp-Image-LNvd-DV.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/sgsG1GC9/temp-Imagey4d-Kd-Q.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/rpzmtSnW/temp-Image-QAGr-Fj.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/05Szf080/temp-Image-LGa-S9y.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/Hs4VGW8J/temp-Imagec-Rv-F99.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 4: Select Departments tab, click Add New Department option, use System Administrators as the role name, select Create Dept optionn and verify that it was successfully created.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/tCHYmnJQ/temp-Imaged-BZyfy.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/rs5zwMhP/temp-Image-S7b-BOE.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>  
<img src="https://i.postimg.cc/ht2vjCrc/temp-Imagep-IWe-J2.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/> 
<img src="https://i.postimg.cc/Z5b0Jk6w/temp-Image-Qi-W76j.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 5: Select Teams tab, select Add New Team option, name the new team Level II Support, navigate to Members tab, add yoourself as a team member and select Create Team.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/FsWpkCSG/temp-Image-Y5-NJj-E.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://i.postimg.cc/Hkr2w04m/temp-Image-QKFscf.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 6: Go to Agents tab and select the option to add a new agent.
</p>
<br />

<p>
</p>
<p align="center"> 
<img src="https://i.postimg.cc/XYZJcLHn/temp-Imagebg-Qxie.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 7: Fill out the name, email and username fields under the Account tab.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/V6YB651r/temp-Image-Nc3-MAc.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 8: Select Set Password, choose a Password, uncheck "Send the agent a password reset email" and "Require password change at next login" and select "Set".
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/PJB9w1Sr/temp-Imagem22h6-X.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/VsT3pczQ/temp-Image-V05-QZc.avif
" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 9: For user 1, on the Acccess Tab, select System Administrators under the Department menu, Senior Admin for the Role menu and navigate to the Teams tab, select Level II Support and click "Create".
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_fe23c182c7554a7bafc9b618fdd503e3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 10: Create a new agent and go thru the same password process as in Step 7. Select Support and View Only  under the Department menu, Senior Admin for the Role menu and Support under Extended Access. Click Create.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5334c985c058497e9b9b83da16689691~mv2.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 11: Enter a password and click on "Set."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_4bf53e313ec44a43b2d8f501f9ae5b01~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 12: For Agent 1, under the "Access" tab, assign them to the System Administrators department with a Senior Administrator role. For extended access, add them to Support.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f8c57363cdb24bf5a72f7becd018ad21~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 13: Keep all permissions under the "Permissions" tab the same, and for teams, add Agent 1 to the Level II Support team.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_4c84c4198f724d898737b69d436d6609~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_70de6927774c4bb9888b9b1c654e8d9e~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 14: Add Agent 2 to the Support department with an "Expanded Access" role and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_dd38ba79bd564a4bb8f4cecb67463b3f~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 15: Keep all permissions the same and add Agent 2 to the Level I Support team, then click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5b5c19cdb85e418a9fce6be892155a46~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_483bc29a100c48118db222b87db8e1fa~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 16:  Create Agent 3 and choose "Maintenance" as their department, "Senior Administrator" for their role, and no extended access.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_a0890ff0a09e4fe293ae39f52d8e00d3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 17: Add Agent 3 to the Level II Support team and click on "Create."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_09ea5aaa4fd144c7996262fbb0a404b0~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_9fb7a351078f4627a6288eb7782b2bb6~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_43c4003ac2c74c499da2c80d8fd901dd~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 18: Go to the Agent panel, then click on "Users," and add the users who will be creating support tickets.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_7bd64b0f4d4c4ce0b190347c39690051~mv2.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_d5665ce0498d4af0b782c126cf712ae0~mv2.png" height="50%" width="50%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 19: Fill out the text input fields and click "Add user" to create two users.
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5700366e1670403f83d69c7144ce39f1~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 20: Return to the admin panel to create SLAs (service-level agreements).
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_5c0e0015dda64269aa8ecf1c6cdda4bf~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_b627d99bd74a46f585eeeb126298ccee~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 21: Navigate to "Manage" and then "SLA," and create three distinct SLA plans by clicking "Add new SLA Plan."
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_dd286a07258e40b78b9e57209637f4b3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 22: Create SLA 1 and name it SEV-A. Set the grace period to one hour on a 24/7 schedule, and then click "Add Plan."
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_88e5750a3fe947a18d58142c6ff3aea7~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 23: Create SLA 2 and name it SEV-B. Set the grace period to four hours on a 24/7 schedule.
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_ef71d2c8792242d28a71e2f4994c3bf3~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 24: Create the last SLA, which is less severe, and name it SEV-C. Set the grace period to eight hours, Monday through Friday from 8 AM to 5 PM.
</p>
<br />

<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_69aa8d9e70fb4855b6299d4af995c519~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 25: Proceed to create various help topics by clicking on the "Help Topics" tab.
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_94778f580b0a437486507b075a049bc7~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_cbca1f2db51b49a8881b81695d30429b~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 26: Click on "Add new help topic," name it "Personal Computer Issues," and then click "Add topic."
</p>
<br />

<p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f8e34d00109743bebc7170ece2721e3f~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_3ec65e833f76472e8676c998799b256b~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p align="center"> 
<img src="https://static.wixstatic.com/media/2ebf04_f9bafab7ed2e453e9ef2a85784b46ddd~mv2.png" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 27: Add three more help topics with the following names:
<ul>
  <li>Password Reset</li>
  <li>Equipment Request</li>
  <li>Business Critical Outage</li>
 </ul> 
</p>
<br />

<p align="center">🌎 <b><i>There is nothing permanent except change. ~ Heraclitus</b></i> 🏛</p>
<br />
<p align="right"> Next: <a href="https://github.com/stevennocent/ticket-lifecycle"
>osTicket: Ticket Lifecycle Examples</a></p>
