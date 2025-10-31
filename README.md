<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (25H2)

<h2>List of Post-Installation in 5 Clear Steps</h2>

1. Access the osTicket System
2. Configure Access Control and Structure
3. Configure User Access Settings
4. Add Agents and Users
5. Define SLAs and Help Topics

<h1>Installation Steps (Images & Explanations)</h1>
<h2>1. Access the osTicket System</h2>
<p>
<img width="2690" height="1252" alt="image" src="https://github.com/user-attachments/assets/ac139edf-bbfe-4a2a-91c9-59b6e6d0d768" />
</p>
<p>
Description: Accessing the Admin Panel, which is used by administrators to configure system settings, manage agents, SLAs, and help topics.
</p>
<br />
<img width="2730" height="1054" alt="image" src="https://github.com/user-attachments/assets/161b43d8-89a0-43c2-9269-05d82a47e680" />
</p>
<p>
Description: Accessing the Agent Panel, which is used by support staff to handle tickets, reply to users, and manage workload.
</p>
<br />
<img width="2666" height="1406" alt="image" src="https://github.com/user-attachments/assets/1648f8f4-d5b4-4fd7-b7a7-1385425502dc" />
</p>
<p>
Description: Accessing the End User Portal, which allows customers to submit new support tickets, track existing requests, and communicate with support staff through a web-based interface.
</p>
<br />

<h2>2. Configure Access Control and Structure</h2>
<p>
<img width="2596" height="1384" alt="image" src="https://github.com/user-attachments/assets/cfe410e4-660a-41c7-bf5e-9e9af2c9dd7e" />
</p>
<p>
Description: Adding a new "Supreme Admin" role, that has 0 permission restrictions. 
</p>
<br />
<p>
<img width="2710" height="1650" alt="image" src="https://github.com/user-attachments/assets/139c1dfa-9080-4cc9-b0f4-6abae632e8c6" />
</p>
<p>
Description: Adding a new "SysAdmins" department with a "Top-Level Department" status.
</p>
<br />
<p>
<img width="2716" height="1608" alt="image" src="https://github.com/user-attachments/assets/06513b7f-e6d9-4cf2-89e7-fa60da51d987" />
</p>
<p>
Description: Adding an "Online Banking" team.
</p>
<br />

<h2>3. Configure User Access Settings</h2>
<p>
<img width="2614" height="1600" alt="image" src="https://github.com/user-attachments/assets/fc9b509a-9d84-471f-b1cd-ed438db56cb3" />
</p>
<p>
Description: Making sure the "Registaration Required" section in the user settings is unchecked, at least for the sake of this project.
</p>
<br />

<h2>4. Add Agents and Users</h2>
<p>
<img width="2578" height="1690" alt="image" src="https://github.com/user-attachments/assets/794a10a7-2219-4140-9dce-e111c75dec2b" />
</p>
<p>
Description: Adding an agent who is part of the "Online Banking" team, who is assigned to the "SysAdmins" department, with a "Supreme Admin" role. 
</p>
<br />
<p>
<img width="2682" height="1678" alt="image" src="https://github.com/user-attachments/assets/6af4b0f7-2291-4525-9fc6-96365ec9af65" />
</p>
<p>
Description: Adding an agent who is assigned to the "Support" department, with a "View Only" role. 
</p>
<br />
<p>
<img width="2624" height="1480" alt="image" src="https://github.com/user-attachments/assets/fbba8d15-95ce-44f9-849a-f9dccf2f8cf8" />
</p>
<img width="2682" height="1444" alt="image" src="https://github.com/user-attachments/assets/10dca502-1e17-4c72-947f-4e4daeb8a9ae" />
</p>
<p>
Description: Adding Users (customers) who can create tickets. 
</p>
<br />

<h2>5. Define SLAs and Help Topics</h2>
<p>
<img width="2636" height="1586" alt="image" src="https://github.com/user-attachments/assets/5a3dbef5-aa04-4d1f-bd67-1e56836a8570" />
</p>
<p>
<img width="2656" height="1598" alt="image" src="https://github.com/user-attachments/assets/03de9c82-db04-4554-8e75-cf3c499d68d4" />
</p>
<p>
<img width="2698" height="1582" alt="image" src="https://github.com/user-attachments/assets/bf987d33-02d3-4398-b7a2-98f248e316fb" />
<p>
Description: Configuring SLA's of various "severities" with according grace periods and schedules. 
</p>
<br />
<p>
<img width="2704" height="1590" alt="image" src="https://github.com/user-attachments/assets/1ed9f8a3-934a-49a6-bffe-75daebc3682f" />
</p>
<p>
<img width="2634" height="1568" alt="image" src="https://github.com/user-attachments/assets/aa176d2b-3160-4945-b8f3-ad672e19b194" />
</p>
<p>
<img width="2702" height="1612" alt="image" src="https://github.com/user-attachments/assets/dd8e50ea-265b-4252-8ad8-829d29859a54" />
</p>
<p>
<img width="2634" height="1568" alt="image" src="https://github.com/user-attachments/assets/aa176d2b-3160-4945-b8f3-ad672e19b194" />
</p>
<p>
<img width="2634" height="1568" alt="image" src="https://github.com/user-attachments/assets/aa176d2b-3160-4945-b8f3-ad672e19b194" />
</p>
<p>
Description: Configuring Help Topics for when users create a ticket.
</p>
<br />

<h1>Final Result:</h1>
<h2>A fully configured osTicket environment is established with defined access roles, structured departments, service level agreements, and organized user management—creating a functional and professional help desk system suitable for real-world IT operations.</h2>
