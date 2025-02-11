<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket - Post Installation Setup</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
  
<h2>Post-Install Configuration Objectives </h2>

- Configure Roles (For Grouping Permissions)</b>
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA (Service Level Agreement)

<h2>Post-Install Configuration Objectives </h2>

- Configure Roles (For Grouping Permissions)
- Configure Departments
  

<p>
When we have our osTicket open the first thing we want to do is Click admin panel in the top right so we can configure all the permissions and rules like Roles, Departments, Teams, Agents, Users, and SLA (Service Level Agreement). When you click admin panel your screen should change and put you in the settings and the admin panel button now says Agent panel button. For this tutorial we are going to make one or two entities in each category so the next lab of Ticket Life Cycle example we can show what all the different components do and how it affects the ticketing software and user/agent interface.
</p>
<br />

![image](https://github.com/user-attachments/assets/991b8f89-4436-4c4a-8c08-337f6619b255)
![image](https://github.com/user-attachments/assets/9f321774-b577-4c08-9bd5-389252e49e7a)


</p>
<p>
The first Configuration I am going to demonstrate is Departments. In the same row as settings select Agents and in the row below Settings and Agents select Departments. Now click Add new Department. Now we will enter settings
</p>
<br />

![image](https://github.com/user-attachments/assets/5310143d-e0cc-4b95-a8b9-e090cc61eeed)

<p>
It will now bring up a settings page for us to enter the settings information about this department. I will enter in a bunch of sample settings and then click on Access. When we click Access this is where we would select the Agents assigned to this department but we haven't created any yet so there nothing to put. I will no click create Department and it will take you back to the departments screen before I clicked Add New Department. I can now see the Department for IT has been created.
</p>
<br />

![image](https://github.com/user-attachments/assets/c805ff52-3ed1-4c30-99ec-ebece189fc20)
![image](https://github.com/user-attachments/assets/43bfa9d5-21db-4999-b738-391e38cc51f4)
![image](https://github.com/user-attachments/assets/13061899-72aa-4998-9ebf-9f5588469f33)

<p>
Now on this same screen in the tab where we selected Departments we will now select Agents and click Add New Agent. Now here is where an Agent is added and you would add the employees information, access, and permissons. From here you can select what permission or access they have to the ticketing system. You can even assign them to certain teams which we will be creating later. This is useful for reasons like if you need this employee to be an admin and oversee and edit Users and Groups and Permissions or maybe this is a brand new employee who should only see and work on tickets assigned to them or their team.
</p>
<br />

<p>
For this example I will be making the Agent John Doe and give him Administartor Status. After the account info has been entered and status set we will click on Access.
</p>
<br />

![image](https://github.com/user-attachments/assets/b4284514-a104-48fa-9e04-ad28107e2bbb)






