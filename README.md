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
<img src="https://i.postimg.cc/VsT3pczQ/temp-Image-V05-QZc.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 9: For user 1, on the Acccess Tab, select System Administrators under the Department menu, Senior Admin for the Role menu and navigate to the Teams tab, select Level II Support and click "Create".
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/YSFkRSQD/temp-Imaged-R2k-RU.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/PxkHRk4X/temp-Image-ALl-BLn.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/qRXrfZb8/temp-Imagepk-Nins.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 10: Create a new agent and go thru the same password process as in Step 7. Select Support and View Only under the Department menu, Senior Admin for the Role menu and Support under Extended Access. Click Create.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/YSFkRSQD/temp-Imaged-R2k-RU.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/PxkHRk4X/temp-Image-ALl-BLn.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/qRXrfZb8/temp-Imagepk-Nins.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 11: Create a new agent and go thru the same password process as in Step 7. Select Support and View Only  under the Department menu, Senior Admin for the Role menu and Support under Extended Access. Click Create.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/ZKtxhqzG/temp-Image-Ho-I20-H.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/kgwQ8FRC/temp-Image8p-AADr.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 12: Navigate to Agent panel, selecct the Users tab and click on Add user.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/KYHW2gbP/temp-Imagev5-Cdng.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
<img src="https://i.postimg.cc/rmRPFFyv/temp-Image-Xzrn8m.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 13: Create a user email address and full name and click Add User. Create two different users.
</p>
<br />

<p>
<p align="center"> 
<img src="https://i.postimg.cc/SQZ52F7K/temp-Image1m-JNHK.avif" height="80%" width="80%" alt="osTicket: Post-Installation Config"/>
</p>
<p>
Step 14: Navigate back to the Admin panel, select the Mannage tab and select SLA.
</p>
<br />
