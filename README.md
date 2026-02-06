# IT-HelpDesk-Simulation

### Ticket #1 - File Restore

**Ticket Detail:** - The user deleted a file from a shared folder and wants it back

**Steps**
- 1. Check if it is in the recycling bin.
- 2. I would go back one directory to the folder that contained the deleted file and enter the folder's properties and restore the file from the preious version section

<img width="365" height="480" alt="Screenshot#1" src="https://github.com/user-attachments/assets/e2e56541-ea38-4158-ab3f-1be699774a08" />

### Ticket #2 - Admin Rights and Remote Access onto machine

**Ticket Detail:** - User has requested to gain Admin rights and the ability to remote into his machine

**Steps**
- 1. Grant admin rights by going into computer management, under users & groups, select groups, and look for administrator, right click and select properties, and add the user as an admin
- 2. Search advanced system settings and goto into the remote tab and enable remote connections to this computer
 
<img width="991" height="709" alt="Screenshot#2" src="https://github.com/user-attachments/assets/9ddc1c03-1f92-4462-8953-01e7cfb4e72c" />

### Ticket #3 - PC having domain issues

**Ticket Detail:** - The user is unable to log into his computer because his PC has fallen off the domain

**Steps**
- 1. Verify that the user's PC is no longer on the domain by checking Server Manager and under AD's users and computers
- 2. If the user's PC is no longer on the domain, we would have to manually log onto the user's PC using a local admin account
- 3. After logging in, we would join the PC into a workgroup and restart the computer, then rejoin the PC into the domain
- 4. Verify by relogining as the user and checking on your server that the PC is in the domain

<img width="434" height="494" alt="Screenshot#3" src="https://github.com/user-attachments/assets/aeedbfc7-8f68-4111-92a9-2c29b8ede6f9" />

<img width="409" height="471" alt="Screenshot#4" src="https://github.com/user-attachments/assets/7d9c932a-51d4-4a49-970a-5894a6683f5a" />

<img width="750" height="524" alt="Screenshot#5" src="https://github.com/user-attachments/assets/a9e64ab8-8d05-4ee9-8ebd-917c8012828e" />

### Ticket #4 - New User

**Ticket Detail:** - There is a new hire at the company, and we need to set up the PC for them

**Steps**
- 1. Join the domain
- 2. Create an account for the user in Active Directory

<img width="433" height="375" alt="sc1" src="https://github.com/user-attachments/assets/5f84ecd2-8922-4179-a7fe-01d3558f5743" />

- 3. Create a security group for HR and add the user to the security group

<img width="396" height="453" alt="sc2" src="https://github.com/user-attachments/assets/d1d88656-7e1b-46ba-896c-e48d9f559ed2" />

- 4. Then, create a shared folder called HR and add the security group to it, and make sure its NTFS permissions are correct

<img width="766" height="361" alt="sc3" src="https://github.com/user-attachments/assets/3e40af61-42d7-4852-9197-2889c14d7874" />

- 5. Log in as the new user to make sure everything is working and map the drive of the user to their department

<img width="1021" height="718" alt="sc4" src="https://github.com/user-attachments/assets/7ec83ce6-6755-4c7b-9ef0-25f107b2bf1f" />

### Ticket #5 - Unable to log in

**Ticket Detail:** - The user has forgotten her password and has locked their account due to multiple unsuccessful attempts

**Steps**
- 1. Head to Active Directory Users and Computers
- 2. Click on the user's profile
- 3. Click on reset password, unlock the account, and prompt the user to create a new password upon login

<img width="751" height="523" alt="pic#1" src="https://github.com/user-attachments/assets/427211ba-8f36-4b13-ab22-fbf288297605" />










