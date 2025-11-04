User & Group Management with Access Control – Linux Project
🎯 Project Overview

This project demonstrates Linux user & group management, file permissions, and ACL (Access Control Lists) for secure access control in a multi-user system.

🏫 Submitted By

Riya
BCA 5th Semester
UID: 23BCA10126
Section: 23BCA-2’B’

👨‍🏫 Submitted To

Mr. Rajat Kapoor
Assistant Professor, UIC

📌 Aim

To manage users, groups, and file permissions in Linux using commands such as useradd, groupadd, chmod, chown, setfacl, and getfacl.

🧰 Tools & Commands Used
Command	Purpose
useradd	Create user
groupadd	Create group
passwd	Set password
chmod	Change permissions
chown	Change owner/group
setfacl	Set ACL permissions
getfacl	View ACL permissions
🧠 Steps Performed
sudo groupadd 23BCA
sudo useradd -m -g 23BCA 23vr
sudo passwd 23vr
sudo mkdir /shared_folder
sudo chown :23BCA /shared_folder
sudo chmod 770 /shared_folder
sudo setfacl -m u:student:rwx /shared_folder
getfacl /shared_folder
sudo userdel -r 23vr
sudo groupdel 23BCA

🔄 Flow Chart
Start
 ↓
Create Group & Users
 ↓
Assign Permissions
 ↓
Apply ACL
 ↓
Verify Access
 ↓
End

🚧 Challenges

Understanding permission levels (r-w-x)

Handling permission errors

Learning ACL commands

Structuring users & groups correctly

📚 Learning Outcomes

✔ Linux User & Group Administration
✔ File Permissions & Access Control
✔ ACL Security Implementation
✔ Practical System Administration Skills

✅ Conclusion

This project strengthened understanding of Linux security and user access management, helping build real system-admin skills.
