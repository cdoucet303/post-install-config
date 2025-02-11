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
For this example I will be making the Agent John Doe and give him Administartor Status. After the account info has been entered and status set we will click on Access. Now I see it lets me select a department for my Agent and what kind of Access they should be allowed. For this Lab I will choose the department I just made and give the Agent All Access. It even gives us an option to add this Agent to an additional department but for this lab we will just do one. Now I will select Permissions in the same row of tabs as Account and Access.
</p>
<br />

![image](https://github.com/user-attachments/assets/b4284514-a104-48fa-9e04-ad28107e2bbb)

![image](https://github.com/user-attachments/assets/83df74e5-7a18-4b00-9381-aa04001b9903)

<p>
For Permissions it will display 4 tabs under the previous row of tabs and it shows Users, Organizations, Knowledgebase, and Miscellaneous. To show each tab with each option for permissions would be tedious so I will show a screen shot of just the User tab permissions and just know each tab has about the same list with checkmarks to select if you want your agent to have certain Permissions. After the permissions have been selected we will now proceed to the Teams tab.
</p>
<br />

![image](https://github.com/user-attachments/assets/d514e7f1-da19-4128-a0a9-bdf7cf807fe4)

<p>
I have not yet created a team but there is a default team already made called Level 1 Support. For this lab I will select that one but will still proceed to make another Team later in this lab. After the Team is selected click on add and we are good to go and hit create on the bottom and create our first Agent!
</p>
<br />

![image](https://github.com/user-attachments/assets/1c5f0052-1962-45ec-bb27-844b87f40a5a)


<p>
For the sake of this lab I am going to make another Agent called Jane Doe with less permissions than John Doe and assign this agent to the team we are about to make. Instead of Administrator status I will be selecting the status of "Limit ticket access to ONLY assigned tickets" to demonstrate the access and permissions.
</p>
<br />

![image](https://github.com/user-attachments/assets/7eebd1a6-bf89-4c37-8b8e-23c901064151)



<p>
We will now click the Teams tab on the second row of tabs and Add a New Team. For this lab I am going to name this one New Employees and add Jane Doe to it and click create.
</p>
<br />

![image](https://github.com/user-attachments/assets/da79aabf-fc22-40f2-8fff-527f91199bdb)

![image](https://github.com/user-attachments/assets/f1471f7a-95d1-48e2-95b3-a3fcca7e9c1b)



<p>
I have not yet created a team but there is a default team already made called Level 1 Support. For this lab I will select that one but will still proceed to make another Team later in this lab. After the Team is selected click on add and we are good to go and hit create on the bottom and create our first Agent!
</p>
<br />




<p>
I have not yet created a team but there is a default team already made called Level 1 Support. For this lab I will select that one but will still proceed to make another Team later in this lab. After the Team is selected click on add and we are good to go and hit create on the bottom and create our first Agent!
</p>
<br />
