# kest2_Verkefni6_oryggismal



# 13.2.3.7 Lab – Bitlocker and Bitlocker To Go.
--------------------
### 1. Question: Why is it important to save a BitLocker recovery key?
Answer: The recovery key is needed for you to gain access to the computer in the event the password is forgotten.

### 2. Question: What is the function of a TPM in relation to BitLocker?
Answer: Trusted Platform Module (TPM) can be used to store the disk encryption key so it can tie use of the disk to a specific computer.


# 13.3.2.5 Lab – Configure Windows Local Security Policy.
--------------------
## Step 3:  Configure the Password Policy security settings.

### 1. Questions:
  Maximum password age blank: 90 <br />
  Minimum password age blank: 1 <br />
  Minimum password length blank: 8 <br />
  Password must meet complexity requirements: Enabled
  
## Step 4:  Configure the Account Lockout Policy security settings.

### 2. Question: According to the security policy in Step 1, how many times is a user allowed to attempt to login before the account is locked?
Answer: 5 tries before lock

### 3. Question: How long should the user have to wait before attempting to log back in?
Answer: 5 minutes


# Step 6:  Configure additional Local Policies security settings.
--------------------

### 1. Question: Are there any you would recommend changing? Why?
Answer: The domains trusted to authenticate logon attempts. So, The student might recommend that only the Administrator group be allowed access.

### 2. Questions:
Policy:
-----
   Devices: Allow undock without having to log on
   
   Interactive logon: Message title for users attempting to log on
   
   Change the Interactive logon: Message text for users attempting to log on
   
   Interactive logon: Prompt user to change password before expiration


Security Setting:
-----
   Disabled
   
   Caution
   
   Your activity is monitored. This computer is for business use only.
   
   7 days
   
   
# 13.3.3.6 Configure Users and Groups in Windows.
--------------------
## Part 1:  Create New Users

## Step 1:  Access Local Users and Groups Manager.
### 1. Question: What are the names of the accounts listed?
Answer: ->

  Administrator.
  
  DefaultAccount.
  
  Guest.
  
  testUser.
  
  testUser2.
  
  tryggvi þor.
  
  user1.
  
  verkuser.
  
  WDAGUtility.

### 2. Question: Select the Groups folder. Name five groups from the list.
Answer: ->

  Administrators.
  
  Users.
  
  Guests.
  
  Event Log Readers.
  
  Power Users.

### 3. Question: Which group does your account belong to?
Answer: Administrators.

## Step 2:  Create new users.
### 4. Question: What is Student01 required to do when logging in the first time?
Answer: Change the password.

### 5. Question: What group does User01 belong to?
Answer: Users.

### 6. Question: From the description, can the members of the Users group make system wide changes? What can the Users group do on the computer?
Answer: NO.

### 7. Question: Who are the group members?
Answer: ->

  Staff01
  
  Staff02
  
  Student01
  
  Student02
  
  test User
  
  test User2
  
  user1
  
  verkuser
  
  ## Step 3:  Verify user and group permissions.
  ### 8. Question: Were you successful in creating the new account as a member of the Users group? Explain.
  Answer: NO, members of the (users) group do not have permision to create now users, becouse it will affect the computer.
  
  ### 9. Question: Were you able to navigate to www.cisco.com? Explain.
  Answer: YES, members of the (users) group can use the internet.

## Part 2:  Create New Groups.

### 10. Question: With the group ITEStaff highlighted, what can the members do in this folder?
Answer: members of the (ITEStaff) group have, read & execute, list folder contents, and read permissions

### 11. Question: Which additional checkbox would you select?
Answer: Select (Full Control).

## Part 3:  Modify User and Group Permissions.

### 12. Question: Navigate to the folder C:\Students. Create a folder named Student02 and create a text document in the folder.
Were you successful? Explain.
Answer: YES. users it the group (ITEStudent) hav full control ower that folder.

### 13. Question: Navigate to the folder C:\Staff. Create a folder named Student02 and place a text file in the folder.
Were you successful? Explain.
Answer: Yes and NO. users in the group (ITEStudent), Student01 has no access to the Staff folder, but the user has full control in the Students folder.

### 14. Question: Are you able to access the content in the Student01 and Student02 folders? Explain.
Answer: Yes and NO. As a user in the group ITEStudent, Student02 still has access to Student02 folder, but there is no access to Student01 folder.

### 15. Question: Were you able to access the content in the folders Staff, Student\Student01 and Student\Student02? Explain.
Answer: Yes. As a user in the group ITEStaff, Staff01 has all the content in C:\Staff and C:\Student. The group permission did not deny write access to the Student’s folders.

## Step 2:  Disable a user account.

### 16. Question: Can you log on as Staff02? Explain.
Answer: No. Because the account has been disabled.

## Reflection Questions.

### 17. Question: How would you give administrative privileges on the local computer to all the members of ITEStaff?
Answer: The members of the group ITEStaff inherits local administrative privileges when it is added to the built-in group Administrator. To change group permission, navigate to Control Panel > Administrative Tools > Computer Management > Local Users and Groups > right-click Add to Group. Click Add to add ITEStaff to the group Administrator.

### 18. Question: How would you deny access to a file for everyone except the owner?
Answer: In the file properties window, give full control to the owner and explicitly deny all access to other groups and users.


# 13.3.4.6 Lab - Configure Windows Firewall.

### 1. Question: Under PC-1, are you able to see the shared folder Cisco?
Answer: True.

### 2. Question: What are the benefits of Windows Firewall?
Answer: It can prevent hackers or malicious software from gaining access to your computer through the internet or a network.

### 3. Question: Describe a negative consequence of having too many exceptions.
Answer: having to many exceptions will put the computer at higher risk of attacks.

### 4. Question: Can you connect to PC-1 and view the Cisco shared folder?
Answer: NO.

### 5. Question: Did you receive an error message on PC-2? If so, what was the Error message?
Answer:  Windows cannot access PC-1.

### 6. Question: Can you connect to computer 1? Explain.
Answer: Yes, because PC-1’s File and Printer Sharing is not being blocked by the firewall.

### 7. Question: List the short name of four services that are available in the Customize Service Settnigs window.
Answer: AxinstSv, AjRouter, Appinfo, ALG.

### 8. Question: List four of the Specific ICMP types.
Answer:Packet Too Big, Source Quench, Echo Recuest, Time Exceeded.

## Reflection Question.

### What are some possible reasons you may need to make firewall changes?
Answer: You may be required to make firewall changes to allow some apps to function correctly

take! pass:  Cisco12345







