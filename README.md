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
A new employee joins the Sales department and requires an Active Directory account for onboarding.  <br />

In this exercise, I:</b> 

- Created a new Active Directory user account.
- Assigned the appropriate username based on company naming conventions.
- Configured an initial temporary password.
- Required the user to change their password at first logon.

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser1.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser2.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>

<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser3.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Congifuring Group Membership</b> <br/>
The employee also requires access to Marketing department resources.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser4.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

The "Member Of" tab was chosen then a group added. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser5.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

"Check Names" option was chosen for marketing to verify the group was correct completing group configuration.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser6.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Deleting and Disabling User Accounts</b> <br/>
HR has notified me that one employee will no longer will be with the company and another will be taking a temporary leave. I am tasked with deleting and disabling their accounts. First, I will delete Robert's account to take effect immediately. I right-click on the user and choose delete.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser7.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

For the user that will be taking a temporary leave, I right-click and choose disable. Upon the employee's return, I will enable the user to restore accessibility. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser8.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Unlocking Account and Resetting Password</b> <br/>
An employee called and stated that her account has been locked out due to multuple log in attempts and forgetting her password. A request was made to also reset the password. I first right-click on users and find the name.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser9.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

I navigate to the account tab and choose the box "Unlock Account" and click apply successfully unlocking the account. This step can be done if the user simply needs to unlock the account if password reset is not needed. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser10.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

I then proceed with right-clicking the user and choose the reset password option. <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser11.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

Password has been chosen and the user has been notified to change the password at next logon. Explaining to the user a password that is complex yet easy to remember is advised to avoid situations like this in the future. Unlocking the account can also be done when resetting password.  <br />
<br />
<p align="center">
<img src="https://github.com/DanielYoon82/ActiveDirectory/blob/main/images/ActiveDirectoryUser12.jpg" height="85%" width="85%" alt="Disk Sanitization Steps"/>
</p>
<br />

- <b>Summary</b> <br />
I demonstrated using Windows Active Directory with modeling a VM in creating, configuring, deleting, and disabling user accounts. In addition, unlocking and resetting a password was carried out using real-world scenarios. These common tasks are vital to user management protocol and done offhand frequently. 
<br />
<br />
