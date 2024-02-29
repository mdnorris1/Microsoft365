# Microsoft 365 (Azure/Entra/Purview)

Cloud Security and Compliance

Microsoft 365 are automatically using Azure AD, so you can access Azure Entra AD features and services through either the Microsoft 365 admin portal or through the Azure portal. 

Scenario 1: Account configuration
•	Create users, add to groups, assign licenses.
•	Configure authentication process by enabling password reset and configuring the settings.
•	Add users to Self-service password reset group.

Scenario 2: Analytics 
Use the Audit logs and the Usage & insights data associated with password resets by users.

Scenario 3: Set up Multi-Factor Authentication (MFA)
Create a policy that will require a user to go through multi-factor authentication when accessing any of the Microsoft Admin portals

Scenario 4: Privileged Identity Management (PIM)
Configure one of your users, Diego Siciliani, with a Microsoft Entra user administrator role, through Privileged ID management (PIM). With user admin privileges, Diego will be able to create users and groups manage licenses, and more. Both the admin and the user, Diego, must be configured for Microsoft Entra ID P2 licensing.

Scenario 5: Compliance
Create a Data Loss Prevention Policy and check existing ones are suitable.

<br>
<br>

Scenario 1
Create users




<br/>
<img src="assets/Picture1.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br/>
<img src="assets/Picture2.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Begin auditing user and admin activity to enable logs for analysis.

<br/>
<img src="assets/Picture3.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Assign licenses.

<br/>
<img src="assets/Picture4.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture5.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture6.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Next, I configured the authentication methods and settings. 
<br/>
<img src="assets/Picture7.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture8.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture9.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture10.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture11.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture12.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br>

Add users to Self-service password reset group.
<br>

<br/>
<img src="assets/Picture13.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture14.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture15.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture16.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture17.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br>

Scenario 2: Analytics 
Use the User sign-in logs, audit logs and the Usage & insights data associated with password resets by users.
<br>

<br/>
<img src="assets/Picture18.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture19.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture20.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture21.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture22.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture23.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture24.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture25.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>
Scenario 3: Multi-factor Authentication
Create a policy that will require a user to go through multi-factor authentication when accessing any of the Microsoft Admin portals
<br>

<br/>
<img src="assets/Picture26.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture27.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture28.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture29.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture30.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture31.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture32.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture33.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>
Scenario 4: Privileged Identity Management (PIM)
Configure one of your users, Diego Siciliani, with a Microsoft Entra user administrator role, through Privileged ID management (PIM). With user admin privileges, Diego will be able to create users and groups manage licenses, and more. Both the admin and the user, Diego, must be configured for Microsoft Entra ID P2 licensing.
<br>

<br/>
<img src="assets/Picture34.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture35.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture36.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>

Uncheck the permanently eligible box as this is a time-limited privilege.
<br>

<br/>
<img src="assets/Picture37.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture38.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture39.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>

Scenario 5: Compliance
Create a Data Loss Prevention Policy and check existing ones are suitable.

Go to the Compliance admin centre (Purview) and create custom policy as well as verifying existing ones are correct.
<br>

<br/>
<img src="assets/Picture40.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br>
Click create policy and complete information relevant to your organisation.
Next, check existing policies such as the GDPR one.

<br>
<br/>
<img src="assets/Picture41.png" height="80%" width="80%" alt="ifconfig command"/>
<br />
<br/>
<img src="assets/Picture42.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br>
The i box will give more information but essentially the high confidence setting will mean the system will check for a credit card AND a key word before it creates an alert as part of the DLP.
