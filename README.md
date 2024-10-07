# 13.2.3.7 Bitlocker and Bitlocker To Go

Why is it important to save a BitLocker recovery key?

Without the recovery key, there may be no way to regain access to the encrypted data, leading to potential data loss.

What is the function of a TPM (Trusted Platform Module) in relation to BitLocker?

TPM is a hardware component that enhances BitLocker’s security by storing cryptographic keys securely. It verifies the integrity of the system at startup, ensuring that the 
system hasn’t been tampered with.

# 13.3.2.5 Configure Windows Local Security Policy

How many times is a user allowed to attempt to login before the account is locked?

5 times

How long should the user have to wait before attempting to log back in?

5 minutes

Are there any security settings under User Rights Assignment that you would recommend changing? Why?

Yes, I recommend changing the "Deny logon locally" to restrict guest or unauthorized accounts from logging in locally for enhanced security.


here is the table

Interactive logon: Machine inactivity limit |	1800 seconds 

Interactive logon: Message text for users attempting to log in | Your activity is monitored. This computer is for business use only.

Interactive logon: Message title for users attempting to log in	| Caution:

Interactive logon: Prompt user to change password before expiration |	7 days

Devices: Prevent users from undocking laptops without logging on | Enabled

# 13.3.3.6 Configure Users and Groups in Windows

What are the names of the accounts listed?

Administrator, ITEUser, vidar, Guest

Name five groups from the list.

Administrators, Users, Guests, Backup Operators, Power Users

Which group does your account belong to?

Administrators

bWhat is Student01 required to do when logging in the first time?

Change their password.

What group does Student01 belong to?

Users

From the description, can the members of the Users group make system-wide changes? What can the Users group do on the computer?

No. Users can run most applications but cannot install software or modify system settings.

Who are the group members?

Student01, Student02, Staff01, Staff02

Were you successful in creating the new account? Explain.

No. Users lack administrative privileges to create accounts.

Were you able to navigate to www.cisco.com? Explain.

Yes. Users can access the internet.

With the group ITEStaff highlighted, what can the members do in this folder?

Read, execute, and list folder contents.

Which additional checkbox would you select?+

Full control

Were you successful? Explain.

Yes. Student02 has permission to create files in the Students folder.

Were you successful? Explain.

No. Student02 does not have permission to create files in the Staff folder.

Can you place a text file in the Staff folder? Can you modify the text file in folder Student02? Explain.

No, cannot place a file in the Staff folder due to lack of permission. Yes, can modify the file in Student02 folder.

Are you able to access the content in the Student01 and Student02 folders? Explain.

Can access the content in Student02 folder but not in Student01 due to deny permissions.

Were you able to access the content in the folders Staff, Student\Student01, and Student\Student02? Explain.

Can access the Staff folder but not the content in Student01 or Student02 folders due to deny permissions.

Can you log on as Staff02? Explain.

No. The account is disabled.

How would you give administrative privileges on the local computer to all the members of ITEStaff?

Add the ITEStaff group to the Administrators group.

How would you deny access to a file for everyone except the owner?

Remove all user and group permissions except the owner and grant the owner full control.

# 13.3.4.6 Lab - Configure Windows Firewall

fann engan

# 13.4.1.10 Packet Tracer - Configure Wireless Security

klárað
