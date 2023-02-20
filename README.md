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










take! pass:  Cisco12345







