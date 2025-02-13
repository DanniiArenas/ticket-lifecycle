<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Before Beginning the Lab</h3>

<p>
Before we commence the lab, make sure to login in via the admin panel. Once logged in, go ahead and navigate to the departments section. From here, make sure to delete the maintenance department as we will no longer be needed this department. Also make sure that the system administration department is a 'TOP Level Department' in the configuration settings. We will make sure that our teams are assigned as follows. With one agent per team. This way we can make progress throughout our lab. Below I provided with how the teams portion should look like, and the process of adding a team member.

![image](https://github.com/user-attachments/assets/0fdd6cea-7e44-4276-8b92-e9adfae5b058)
![image](https://github.com/user-attachments/assets/2bc49b73-161a-492c-a7b7-1ab36ab74955)

</p>

<p>
For this intake portion, we will begin by creating a ticket via our osticket 'end user' link. By doing so, once on the website we are going to click on 'open a new ticket'. We are going to be using the 'users' we created in the previous labs. To sign in and create a ticket.

![image](https://github.com/user-attachments/assets/3ab31ff1-aa76-4f22-b0bb-085bcc867a41)

From here, you will begin to fill in the end user information we created from the previous lab. We will also include a helpdesk topic, 'Report a problem'. While our issue is going to be a critical issue; we are simply creating user error which can be common within a helpdesk role. Our issue at has is going to be: 'entire mobile/online banking system is down'. Then we will include a brief description that can help the helpdesk agent; afterwards we will make sure to click on 'create ticket' at the bottom of the page.

![image](https://github.com/user-attachments/assets/fbdb4abc-6e05-4170-9cd4-e8a785f4c569)

Now, we will be going back to the admin portal (make sure you are logged out of the admin credentials). Once you are at the admin portal, we are going to log in as the support team user we created in our previous portion of the lab. Once you are logged in, you should be seeing the new ticket we have made.

![image](https://github.com/user-attachments/assets/54bae39b-1f0c-4eac-9a6f-b35935c85f55)

</p>

<p>
In this section, we will examine the tickets properties. Make sure to go over, the priority, department, SLA, and who the ticket is assigned to. Make changes as necessary.

We will begin by changing the SLA Plan to Sev A. Sev A is our highest SLA possible, since the entire banking system is currently down. Make sure to press update.

![image](https://github.com/user-attachments/assets/d796bb9b-83f4-4f8f-85fe-f35b838bf951)

We will now change the report topic to 'Business Critical Outage'. This alligns with the true problem at hand. We will then assign the ticket to the 'Online Banking Team', with a reasoning as to why we assigned it to the team. We will also be updating the priority, make sure to change it to Emergency Priority and why it is a Emergency Priority ticket.

![image](https://github.com/user-attachments/assets/fcc8f2fd-c0ff-4b64-a177-0f039d54dcce)
![image](https://github.com/user-attachments/assets/d6c031cb-4e4d-475f-abcb-dba049b981ad)
![image](https://github.com/user-attachments/assets/df05d228-1d43-478b-bf25-ddcff03c3404)

Now, we will log in as our other user. This user should be assigned to the online banking team. Once logged in, we will see the ticket labeled as an Emergency.

![image](https://github.com/user-attachments/assets/4ddecfbe-a6c6-4c9a-a222-734a326e0695)

Now we will, assign the ticket to ourselves. Make sure to include a brief description such as 'I will be taking this ticket." We will also post a reply, to document our thoughts and any reasons as to why the online banking portal may be down.

![image](https://github.com/user-attachments/assets/9fbf35f8-5f9a-45d3-b20f-91e489266bb0)

Above we can review the history of the ticket. Now, we will be assuming the issue was one of the updates; and we have rolled back the update. All is now functional. Now, post a reply regarding your findings, and how you solved the issue. Also make sure how you will make sure this issue does not arise again.

![image](https://github.com/user-attachments/assets/cad616ea-1d53-4af0-be6b-f021091e6d8d)

Now we will set the ticket to Resolved status. That is the end of our lab, we will optionally be working on more tickets. The ticket topics will be included below.
</p>
<br />

<h3>Optional Ticket Topics To Work On</h3>

<p>
  accounting department needs adobe upgrade, broken

  CFO’s laptop will no longer turn on

</p>
