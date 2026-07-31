<h1>Home Lab - Active Directory User Administration</h1>

<h2>Project Overview</h2>
This home lab demonstrates common Active Directory administrative tasks performed by IT Support and Help Desk professionals. The project simulates real-world service desk scenarios involving user account management, security, and access administration.  
<br />

<h2>Objectives</h2>
- Create and manage Active Directory user accounts
- Configure user account settings and security options
- Assign security group memberships
- Perform password resets and account unlocks
- Disable and delete user accounts based on business requirements
- Follow common Help Desk administrative procedures

<h2>Environment Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>


- <b>Creating New User Account</b> <br />
A new employee joins the Sales department and requires an Active Directory account for onboarding. First, I create a new Active Directory user account.
</p>  
<br />

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser1.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

Assign the appropriate username based on company naming conventions. <br /> 
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser2.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

Configure an initial temporary password and require the user to change their password at first logon.  <br /> 
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser3.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Congifuring Group Membership</b> <br/>
The employee also requires access to Marketing department resources. First, open the user's account properties  <br />


<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="95%" width="95%" alt="Disk Sanitization Steps"/>
</p>
<br />

Add the user to the Marketing group.
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
