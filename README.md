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



Scenario 1
Create users




We used a netscan command: 


<br/>
<img src="assets/1a.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

We found a computer had an established connection to another system and this was unusual.

<br/>
<img src="assets/connection.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Next, we needed to see the processes / process IDs so ran this code:

<br/>
<img src="assets/processes.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

The cmd.exe stands out as being unusual for every day user interaction.

<br/>
<img src="assets/cmd.exe.png" height="100%" width="100%" alt="ifconfig command"/>
<br />

pstree command provided us with more detail:

<br/>
<img src="assets/pstree.png" height="80%" width="80%" alt="ifconfig command"/>
<br />


Below, you can see that we traced back the parent process for one of the cmd.exe files back to TrustMe.exe. The parent processes helps create a sort of timeline for the processes or actions on the system.

Also, the parent process for TrustMe was Explorer.exe. This means it was invoked by the user on the system, as Explorer.exe is the GUI process for Windows 10.

<br/>
<img src="assets/parent processes.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Using the dlllist command helped look into the TrustMe.exe process a bit further:

<br/>
<img src="assets/dll list.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

<br/>
<img src="assets/dll list 2.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Here you can see the dll's associated with the TrustMe process.

We can also see the command line in this process which is useful as it can tell us where on the system it was executed from.

Finally, let’s look at the use of malfind. This module will look at the processes for any suspicious activities, looking for characteristics used by malware.

<br/>
<img src="assets/malfind.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

We found an executable with Read and Write when such a combination doesn't usually need to occur for everyday user activity.

<br/>
<img src="assets/malfind2.png" height="80%" width="80%" alt="ifconfig command"/>
<br />

Hope you enjoyed the project!
