# osTicket-post-install
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

- Windows 10 Pro (22H2), at least 2vCPUs, 8GB RAM</b>

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/f0fc66e5-55c0-4cd8-8575-f0a35d32da87)

<p>
Login using Admin/Analyst Login Page
</p>
<br />

![image](https://github.com/user-attachments/assets/37a02b60-b721-4106-8e79-91a58feeacab)

<p>
Select Admin Panel 
</p>
<br />


![image](https://github.com/user-attachments/assets/30aa24c0-b30a-45cb-bd31-7ea966651602)

<p>
Select Agents > Roles > Add New Role
</p>
<br />


![image](https://github.com/user-attachments/assets/51dbebf5-e962-46aa-aeb6-346353e6891c)

<p>
Name : Super Admin
</p>
<br />


![image](https://github.com/user-attachments/assets/7a3d1563-5135-407a-b88d-60220065a519)

<p>
Make sure all boxes are checked, then add role
</p>
<br />


![image](https://github.com/user-attachments/assets/44d4f30c-023e-490b-901d-91d90ce33f34)

<p>
Select Agents > Departments > Add New Department
</p>
<br />


![image](https://github.com/user-attachments/assets/58bba36c-2119-4767-b764-ec0de9f88061)

<p>
Parent : Top Level Department 
</p>
<br />

<p>
Name : SysAdmin
</p>
<br />

<p>
Under Access tab make sure all boxes are selected, then add department
</p>
<br />

![image](https://github.com/user-attachments/assets/45d07e42-287d-45c8-930d-dea42ad70e5e)

<p>
Select Agents > Teams > Add New Team
</p>
<br />


![image](https://github.com/user-attachments/assets/8db13f43-7e5b-4677-a680-916630846504)

<p>
Name : Online Banking, then create team
</p>
<br />



![image](https://github.com/user-attachments/assets/64d9f38a-5935-49ec-a3ec-c50d7dc4e8cc)

<p>
Select Settings > Users > User Settings > Make sure Registration Required is checked
</p>
<br />


![image](https://github.com/user-attachments/assets/1428cc1d-bfdb-46f9-8f48-8208e27b6a4d)

<p>
Create a new Agent 
</p>
<br />


![image](https://github.com/user-attachments/assets/b4202a4e-df76-44bf-9e0b-2345f53edead)

<p>
Configure Access
</p>
<br />



![image](https://github.com/user-attachments/assets/e60c4ffb-130e-4e5e-8cb3-7dd96fae23a5)

<p>
Assign to Team > Online Banking
</p>
<br />

![image](https://github.com/user-attachments/assets/3b695f04-816b-430f-bc28-81e336e79e2a)

<p>
Create a new Agent
</p>
<br />

![image](https://github.com/user-attachments/assets/0ca87857-cb59-4514-8cfc-c0318ffb2300)

<p>
Configure Access
</p>
<br />

![image](https://github.com/user-attachments/assets/bee10736-4766-45cd-84f1-1e30c54472b2)

<p>
Select Agent Panel > Users > User Directory > Add User
</p>
<br />


![image](https://github.com/user-attachments/assets/da34e4a6-1ea4-4500-9a0f-5c6beabaf2b6)

<p>
Create User > ! Fill in Phone Number, required for logging into user portal !
</p>
<br />


![image](https://github.com/user-attachments/assets/1285c049-17b4-45aa-b8da-0e6dba6f03d2)

<p>
Create User > ! Fill in Phone Number, required for logging into user portal ! 
</p>
<br />


![image](https://github.com/user-attachments/assets/219e6c56-6476-4209-9c67-032b8c14872b)

<p>
Select Admin Panel > Manage > SLA > Add New SLA Plan 
</p>
<br />


![image](https://github.com/user-attachments/assets/33697716-a23a-4311-9030-471953b38dc1)

<p>
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
</p>
<br />


![image](https://github.com/user-attachments/assets/f21633a6-31c9-408c-9c8f-75c8aa10d09f)

<p>
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
</p>
<br />


![image](https://github.com/user-attachments/assets/a0cc5550-ef7e-4040-82d2-30c83b1d18f6)

<p>
Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />


![image](https://github.com/user-attachments/assets/4ad8532e-1a96-4e74-93ac-2bd903119322)

<p>
Select Manage > Help Topics > Add New Help Topic
</p>
<br />


![image](https://github.com/user-attachments/assets/def4120e-c5f4-42f6-8324-b9a65abedf67)

<p>
Create a Topic : Business Critical Outage > Parent Topic : Report a Problem
</p>
<br />


![image](https://github.com/user-attachments/assets/a3c0ffe0-ad37-40bc-96aa-13b59ca77616)

<p>
Create a Topic : Personal Computer Issues > Parent Topic : Report a Problem
</p>
<br />


![image](https://github.com/user-attachments/assets/7618bf07-4d25-4f1d-8397-632aecc3bf32)

<p>
Create a Topic : Equipment Request > Parent Topic : Report a Problem
</p>
<br />


![image](https://github.com/user-attachments/assets/d10d73ae-aadc-4c7f-bbec-6a4feaaeb1fb)

<p>
Create a Topic : Password Reset > Parent Topic : Report a Problem
</p>
<br />


![image](https://github.com/user-attachments/assets/0982aa2d-77f6-4c7e-b170-1418330bae2c)

<p>
Create a Topic : Other > Parent Topic : General Inquiry
</p>
<br />
