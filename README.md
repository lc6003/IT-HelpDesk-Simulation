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











