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
Answer: Administrators


