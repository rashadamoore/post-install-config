<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=doTWdYMsmjA)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

<ol><li><p><strong>General Settings</strong>:</p><ul><li>Set helpdesk name, default email, timezone, and language.</li></ul></li><li><p><strong>Email Configuration</strong>:</p><ul><li><strong>System Emails</strong>: Add email addresses for support.</li><li><strong>Outgoing (SMTP)</strong>: Configure outgoing email server.</li><li><strong>Incoming (IMAP/POP)</strong>: Enable email fetching for automatic ticket creation.</li></ul></li><li><p><strong>Departments and Teams</strong>:</p><ul><li>Create departments (e.g., Support, Sales).</li><li>Set up teams for cross-department collaboration.</li></ul></li><li><p><strong>Help Topics</strong>: Define help topics for ticket categorization.</p></li><li><p><strong>SLA Plans</strong>: Set up SLA policies for response and resolution times.</p></li><li><p><strong>Ticket Settings</strong>:</p><ul><li>Customize ticket format, status, and client access options.</li></ul></li><li><p><strong>Agent Roles and Permissions</strong>:</p><ul><li>Define roles and assign permissions to agents.</li></ul></li><li><p><strong>User Authentication and Registration</strong>: Enable/disable registration, and set login requirements.</p></li><li><p><strong>Auto-Responder and Alerts</strong>:</p></li><ul><li>Configure alerts for new tickets, responses, and overdue tickets.</li></ul> </ol>

<h2>Configuration Steps</h2>

<p> 
  
![Screenshot (11)](https://github.com/user-attachments/assets/3e4651c4-2a68-4af9-8e0a-d99e2d425d7a)
  
</p>
<p>
  <h3><strong>Set Up Departments and Teams</strong></h3>
<ul><li><strong>Departments</strong>: Organize support requests by creating departments, like <strong>Support</strong>, <strong>Sales</strong>, or <strong>Billing</strong>.<ul><li>Go to <strong>Admin Panel &gt; Agents &gt; Departments</strong> to add new departments and assign department heads.</li></ul></li><li><strong>Teams</strong>: Create teams to handle tickets across departments if needed.<ul><li>Go to <strong>Admin Panel &gt; Agents &gt; Teams</strong> to set up teams and assign agents.</li></ul></li></ul>
</p>
<br />
<p>
  
![Screenshot (14)](https://github.com/user-attachments/assets/a932440e-59d2-4c5e-8316-81ac68338dd4)

</p>
<p>
 <h3><strong>Agent Roles and Permissions</strong></h3> 
<ul><li>Assign roles to agents, defining what permissions they have within departments.</li><li>Go to <strong>Admin Panel &gt; Agents &gt; Roles</strong> to set up roles like <strong>Support Agent</strong>, <strong>Manager</strong>, etc., and customize permissions for each role.</li><li>Assign agents to roles under <strong>Admin Panel &gt; Agents &gt; Agents</strong>.</li></ul>
</p>
<br />

<p>
  
![Screenshot (15)](https://github.com/user-attachments/assets/f6b13c42-ee53-4f8b-8e7c-fe6218eec94c)

</p>
<p>
<h3><strong>Configure SLA Plans</strong></h3>
<ul><li>SLA Plans allow you to set response and resolution timelines for tickets.</li><li>Go to <strong>Admin Panel &gt; Manage &gt; SLA Plans</strong> to create SLA policies like <strong>High Priority (24 hours)</strong> or <strong>Low Priority (72 hours)</strong>.</li><li>Assign SLAs to departments or help topics as needed.</li></ul>
</p>
<br />
<p>
  
![Screenshot (16)](https://github.com/user-attachments/assets/d20e3e0a-f2eb-4822-825a-d2b9cafdc1c2)


</p>
<p>
<h3><strong>Create Help Topics</strong></h3>
<ul><li>Help Topics help categorize tickets, making it easier for users to submit specific types of requests.</li><li>Go to <strong>Admin Panel &gt; Manage &gt; Help Topics</strong> to add topics like <strong>Technical Support</strong>, <strong>Billing Question</strong>, or <strong>Account Assistance</strong>.</li></ul>
</p>
<br />
