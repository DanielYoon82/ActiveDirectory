<h1>Home Lab - Active Directory User Administration</h1>

<h2>Description</h2>
This home lab demonstrates common Active Directory administrative tasks performed by IT Support and Help Desk professionals. The project simulates real-world service desk scenarios involving user account management, security, and access administration.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows 10</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>


- <b>Creating New User Account</b> <br />
A new employee joins the Sales department and requires an Active Directory account for onboarding. First, I create a new Active Directory user account.
</p>  
<br />

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser1.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

Assign the appropriate username based on company naming conventions. <br /> 
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser2.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br /> 

Configure an initial temporary password and require the user to change their password at first logon.  <br /> 
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Congifuring Group Membership</b> <br/>
The employee also requires access to Marketing department resources. First, open the user's account properties  <br />


<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Add the user to the Marketing group.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Verify the group using the Check Names feature.
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser6.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />


- <b>Disabling and Deleting User Accounts</b> <br/>
HR reports that one employee has left the company, while another is taking a temporary leave of absence. First, delete the account of the terminated employee  <br />

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

<br />
Disable the account of the employee on leave. Explained that disabled accounts can be re-enabled when the employee returns. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser8.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Unlocking Account and Resetting Password</b> <br/>
A user contacts the Help Desk after becoming locked out of their account due to multiple failed login attempts. First, locate the user account in Active Directory.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser9.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Unlocked the account through the Account tab. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser10.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Reset the user's password. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser11.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Enabled the User must change password at next logon option.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser12.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Summary</b> <br />
I demonstrated using Windows Active Directory with modeling a VM in creating, configuring, deleting, and disabling user accounts. In addition, unlocking and resetting a password was carried out using real-world scenarios. These common tasks are vital to user management protocol and done offhand frequently. 
<br />
<br />
