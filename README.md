# Microsoft 365 (Azure/Entra/Purview)

<h2>Cloud Security and Compliance</h2>

<h3>Scenario 1:</h3> 

• Account configuration

•	Create new users, add them to groups and assign licenses.

•	Configure authentication process by enabling password reset and configuring the settings.

•	Add users to Self-service password reset group.

<h3>Scenario 2: Analytics</h3> 
Use the Audit logs and the Usage & insights data associated with password resets by users.

<h3>Scenario 3: Set up Multi-Factor Authentication (MFA)</h3>
Create a policy that will require a user to go through multi-factor authentication when accessing any of the Microsoft Admin portals

<h3>Scenario 4: Privileged Identity Management (PIM)</h3>
Configure one of your users, Diego Siciliani, with a Microsoft Entra user administrator role, through Privileged ID management (PIM). With user admin privileges, Diego will be able to create users and groups manage licenses, and more. Both the admin and the user, Diego, must be configured for Microsoft Entra ID P2 licensing.

<h3>Scenario 5: Compliance</h3>
Create a Data Loss Prevention Policy and check existing ones are suitable.

<br>
<br>

<h2>Scenario 1</h2>
Create users

<br>


<br/>
<img src="assets/Picture1.png" width="500" height="40%" width="40%" alt="ifconfig command"/>
<br />

<br/>
<img src="assets/Picture2.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />

Begin auditing user and admin activity to enable logs for analysis.

<br/>
<img src="assets/Picture3.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />

Assign licenses.

<br/>
<img src="assets/Picture4.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture5.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture6.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />

Next, I configured the authentication methods and settings. 
<br>

<br/>
<img src="assets/Picture7.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture8.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture9.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture10.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture11.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture12.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br>

Add users to Self-service password reset group.
<br>

<br/>
<img src="assets/Picture13.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture14.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture15.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture16.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture17.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br>

<h2> Scenario 2: Analytics </h2> 
Use the User sign-in logs, audit logs and the Usage & insights data associated with password resets by users.
<br>

<br/>
<img src="assets/Picture18.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture19.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture20.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture21.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture22.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture23.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture24.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture25.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>
<h2> Scenario 3: Multi-factor Authentication </h2>
Create a policy that will require a user to go through multi-factor authentication when accessing any of the Microsoft Admin portals.
<br>

<br/>
<img src="assets/Picture26.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture27.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture28.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture29.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture30.png" width="800" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture31.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture32.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture33.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>
<h2> Scenario 4: Privileged Identity Management (PIM) </h2>
Configure one of your users, Diego Siciliani, with a Microsoft Entra user administrator role, through Privileged ID management (PIM). With user admin privileges, Diego will be able to create users and groups manage licenses, and more. Both the admin and the user, Diego, must be configured for Microsoft Entra ID P2 licensing. 

<br>

<br/>
<img src="assets/Picture34.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture35.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture36.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>

Uncheck the permanently eligible box as this is a time-limited privilege.
<br>

<br/>
<img src="assets/Picture37.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture38.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture39.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>

<h2> Scenario 5: Compliance </h2>
Create a Data Loss Prevention Policy and check existing ones are suitable.

Go to the Compliance admin centre (Purview) and create custom policy as well as verifying existing ones are correct.
<br>

<br/>
<img src="assets/Picture40.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br>
Click create policy and complete information relevant to your organisation.
Next, check existing policies such as the GDPR one.

<br>
<br/>
<img src="assets/Picture41.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture42.png" width="500" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>
The i box will give more information but essentially the high confidence setting will mean the system will check for a credit card AND a key word before it creates an alert as part of the DLP.
