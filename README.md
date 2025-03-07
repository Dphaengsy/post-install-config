# post-install-config
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



![image](https://github.com/user-attachments/assets/e4bd92ed-a411-403a-87e8-9f18813e6864)




To start of you want to create a new role. to create a new role got to Admin Panel -> Agents -> Roles. Click on Add new role. The new role I created was Supreme Admin. Click on Permission and check every task to allow every possible task.


![image](https://github.com/user-attachments/assets/563b127e-9e78-4e37-950f-2aa29b478d63)



Select the Deparment button in the Agent tab and create a new deparment called SysAdmins. You can add agents in here once we create some

![image](https://github.com/user-attachments/assets/15dd7ade-5790-4e83-8d1c-7274c5753f26)

To create a Team select the team button on the agent tab and create a new team called online banking. You can add agents in here once we create some



![image](https://github.com/user-attachments/assets/255de0d0-8310-402b-8fbf-c856670270bd)



To create agents go to Admin Panel -> Agents -> Add New. Fill in the necessary details, such as the agent's name, email, assigned role, and department, to set up their profile and permissions. I created Mario and Luigi. Mario was put in SysAdmins with Supreme Admin power, and put in  online banking while Luigi was put in Support with all access.





![image](https://github.com/user-attachments/assets/5d461b83-873b-4c2d-a7bc-6fa4cf51aeba)



After that you want to create a User go to Agent Panel -> Users -> Add New. I created one called Peach



![image](https://github.com/user-attachments/assets/2cab823f-a461-45c0-95e0-f70e6906d26f)








Next you want to configure SLA. Go to Admin Panel -> Manage -> SLA. Then create 3 SLA, Sev-A (Grace Period: 1 hour, Schedule: 24/7), Sev-B (Grace Period: 4 hours, Schedule: 24/7), and Sev-C (Grace Period: 8 hours, Business Hours)



![image](https://github.com/user-attachments/assets/1a93d9ff-b2d8-47af-a64d-b43b15dbe891)




Last of all you want to Configure Help Topics (For when users create a ticket). Go to Admin Panel -> Manage -> Help Topics and create 4 new Help Topics called Business Critical Outage, Personal Computer Issue, Equipment Request, and Password Reset




