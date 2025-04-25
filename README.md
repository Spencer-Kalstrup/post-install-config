<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Useful links</h2>
<a href="http://localhost/osTicket/scp/login.php">Admin Login</a>

<a href="http://localhost/osTicket">End User URL</a>

<h2>Step 1 : Configuring Roles</h2>
<p> To Configure roles, start by navigating to the admin panel</p><p>

<img src="https://i.imgur.com/w7pXOSj.png" height="80%" width="80%"/></p>
<p>Click the "Agents" tab, then click "Roles"</p><br />

<p><img src="https://i.imgur.com/m6536GG.png" height="80%" width="80%"/></p>
<p>Click "All Access"
<p><img src="https://i.imgur.com/uNs1eiL.png" height="80%" width="80%"/></p>

<p><img src="https://i.imgur.com/V6SgS1o.png" height="80%" width="80%"/></p>
<p>The permissions tab allows changes to be made to the selected role</p>
<br />

<h2>Configuring Departments</h2>
<p>Click the "Departments" tab</p>
<p><img src="https://i.imgur.com/JzZm1N6.png" height="80%" width="80%"/></p>

<p>Click "Add new department"</p>
<p><img src="https://i.imgur.com/Fs1ZVKY.png" height="80%" width="80%"/></p>
<br />

<p>Enter new department name here</p>
<p><img src="https://i.imgur.com/S0wMbbr.png" height="80%" width="80%"/></p>
<br />

<p>Under the access tab, agents may be added to the new department</p>
<p><img src="https://i.imgur.com/c2wgbqU.png" height="80%" width="80%"/></p>
<br />

<h2>Configuring Teams</h2>
<p>Configuring Teams lets us pull agents from different departments. click the "Teams" tab</p>
<p><img src="https://i.imgur.com/3f3T9Hv.png" height="80%" width="80%"/></p>
<p>Configure Teams (Pull Agents from different Departments) click the "Teams" tab Teams</p>
<br />

<p>Click add new team</p>
<p><img src="https://i.imgur.com/UsvsQwh.png" height="80%" width="80%"/></p>
<br />

<p>Name the new team</p>
<p><img src="https://i.imgur.com/ouTW0Df.png" height="80%" width="80%"/></p>
<br />

<p>Add agents to the new team under the "Members" tab</p>
<p><img src="https://i.imgur.com/C9cGSQ4.png" height="80%" width="80%"/></p>
<br />

<h2>Configuring Agents</h2>
<p>To configure new Agents or Workers, Navigate to the Agents tab</p>
<p><img src="https://i.imgur.com/Y0dw7df.png" height="80%" width="80%"/></p>

<p>Click "Add New"</p>
<p><img src="https://i.imgur.com/FzOfJPK.png" height="80%" width="80%"/></p>

<p>Fill out the following boxes, then click "Set password"</p>
<p><img src="https://i.imgur.com/CwEefJg.png" height="80%" width="80%"/></p>
<br />

<p>Uncheck both boxes and create a password for the new user</p>
<p><img src="https://i.imgur.com/INoXzX5.png" height="80%" width="80%"/></p>
<br />

<p>Navigate to the Access tab, then select the department and role for the new agent (Jane will be in the SysAdmins department and the role will be all access)</p>
<p><img src="https://i.imgur.com/A3wBwKC.png" height="80%" width="80%"/></p>
<br />

<p><img src="https://i.imgur.com/uHXrpIA.png" height="80%" width="80%"/></p>
<p>Under the teams tab, we can assign which team the agent will be assigned to. We can also use the permissions tab to change permissions while creating a new agent.</p>
<br />

<p>Repeat the process for  John Doe, but change the role to "Support" and the role to "View only", so we can observe the differences between roles</p>
<p><img src="https://i.imgur.com/oKHIJ4w.png" height="80%" width="80%"/></p>
<br />

<h2>Configuring Users</h2>
<p>Next, we will configure users a.k.a. customers. Navigate to the agent panel</p>
<p><img src="https://i.imgur.com/CRIHGFj.png" height="80%" width="80%"/></p>
<br />

<p>Click the users tab</p>
<p><img src="https://i.imgur.com/2WYjlA5.png" height="80%" width="80%"/></p>
<br />

<p>Click "Add User"</p>
<p><img src="https://i.imgur.com/SGYZd5x.png" height="80%" width="80%"/></p>
<br />

<p>Enter 2 users, Karen and Ken</p>
<p><img src="https://i.imgur.com/TWAY1Ax.png" height="80%" width="80%"/></p>
<p><img src="https://i.imgur.com/C8ijFu9.png" height="80%" width="80%"/></p>
<br />

<h2>Configuring SLA</h2>
<p>While in the Admin panel, click the "Manage" tab</p>
<p><img src="https://i.imgur.com/caLU1nd.png" height="80%" width="80%"/></p>
<br />

<p>Click "SLA" tab</p>
<p><img src="https://i.imgur.com/ugjqfjP.png" height="80%" width="80%"/></p>
<br />

<p>Click "Add New SLA Plan"</p>
<p><img src="https://i.imgur.com/Ejh4GpM.png" height="80%" width="80%"/></p>
<br />

<p>Enter the following 3 SLA plans</p>
<p>Sev-A (Grace Period: 1 hour, Schedule: 24/7)</p>
<p><img src="https://i.imgur.com/CKbY18n.png" height="80%" width="80%"/></p>
<p>Sev-B (Grace Period: 4 hours, Schedule: 24/7)</p>
<p><img src="https://i.imgur.com/JLckvoq.png" height="80%" width="80%"/></p>
<p>Sev-C (Grace Period: 8 hours, Business Hours)</p>
<p><img src="https://i.imgur.com/jh5oI6Y.png" height="80%" width="80%"/></p>
<br />

<h2>Configuring Help Topics</h2>
<p>configuring help topics helps us organize issues. Start by navigating to the manage tab<p>
<p><img src="https://i.imgur.com/FOI896I.png" height="80%" width="80%"/></p>

<p>Click "Add New Help Topic"
<p><img src="https://i.imgur.com/LKlCpIG.png" height="80%" width="80%"/></p>

<p>Enter names for issue categories such as "Password Reset" or "Business Critical Outage"</p>
<p><img src="https://i.imgur.com/bsdzUQZ.png" height="80%" width="80%"/></p>
<p><img src="https://i.imgur.com/YL6wogX.png" height="80%" width="80%"/></p>
<br />




<h2>Allowing Anyone To Create Tickets</h2>
<p>Start by navigating to the "Settings" tab</p>
<p><img src="https://i.imgur.com/rBSrQPQ.png" height="80%" width="80%"/></p>

<p>Click the "Users" tab</p>
<p><img src="https://i.imgur.com/G51lk8R.png" height="80%" width="80%"/></p>

<p>Ensure "Registration Required" is unchecked
<p><img src="https://i.imgur.com/2m2BjsG.png" height="80%" width="80%"/></p>

<p>We can also change the registration method to suit our needs</p>
<p><img src="https://i.imgur.com/6ELY9pv.png" height="80%" width="80%"/></p>
<br />
