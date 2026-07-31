<h1>Home Lab - Active Directory User Administration</h1>

<h3>Project Overview</h3>
This home lab demonstrates common Active Directory administrative tasks performed by IT Support and Help Desk professionals. The project simulates real-world service desk scenarios involving user account management, security, and access administration.  
<br />

<h3>Objectives</h3>

- Create and manage Active Directory user accounts
- Configure user account settings and security options
- Assign security group memberships
- Perform password resets and account unlocks
- Disable and delete user accounts based on business requirements
- Follow common Help Desk administrative procedures

<h3>Environment </h3>

- Windows Server (Active Directory Domain Services)
- Windows 10 Client
- Active Directory Users and Computers (ADUC)

<h3>Skills Demonstrated </h3>

- Active Directory Administration
- User Account Provisioning
- Password Reset Procedures
- Account Unlock
- Security Group Management
- User Lifecycle Management
- Access Control
- Help Desk Documentation
- Identity and Access Management (IAM)

<h3>Scenario 1 – Creating a New User Account</h3>


- <b>Issue</b> <br />
A newly hired employee in the Sales department requires an Active Directory account to access company resources.
</p>  
<br />

- <b>Actions Performed</b> <br />
- Opened Active Directory Users and Computers
- Created a new user account
- Assigned a username following company naming conventions
- Configured an initial temporary password
- Enabled User must change password at next logon
- Verified the account was successfully created
</p>  
<br />

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser1.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser2.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser3.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>Scenario 2 – Configuring Security Group Membership</h3>
The employee also requires access to Marketing department resources. First, open the user's account properties  <br />

- <b>Issue</b> <br />
The employee also requires access to shared Marketing department resources.
</p>  
<br />

- <b>Actions Performed</b> <br />
- Opened the user's account properties
- Navigated to the Member Of tab
- Added the user to the Marketing security group
- Verified group membership using the Check Names feature
- Confirmed the appropriate permissions were assigned


<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser5.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

Verify the group using the Check Names feature.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser6.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />


- <b>Disabling and Deleting User Accounts</b> <br/>
HR reports that one employee has left the company, while another is taking a temporary leave of absence. First, delete the account of the terminated employee  <br />

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser7.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

<br />
Disable the account of the employee on leave. Explained that disabled accounts can be re-enabled when the employee returns. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser8.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Unlocking Account and Resetting Password</b> <br/>
A user contacts the Help Desk after becoming locked out of their account due to multiple failed login attempts. First, locate the user account in Active Directory.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser9.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

Unlock the account through the Account tab. This step can be done to only unlock the account as well. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser10.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

Reset the user's password. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser11.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

The user must change password at next logon option. Advised the user to create a strong, memorable password to reduce future lockouts. Unlocking the account can also be done here.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser12.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Summary</b> <br />
This lab demonstrates foundational Active Directory administration skills by simulating common IT Support responsibilities. Tasks included creating and managing user accounts, configuring security group membership, disabling and deleting accounts, unlocking locked accounts, and resetting passwords. These administrative tasks mirror everyday responsibilities performed by Help Desk and IT Support professionals in enterprise Windows environments.
<br />
<br />
