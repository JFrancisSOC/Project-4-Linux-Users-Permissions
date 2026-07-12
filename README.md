# Project 4 – Linux Users & Permissions

## Objective

- Understand and practice Linux file ownership and permission settings.
- Learn to navigate user accounts, directories, and modify permissions using commands.

---

## Environment

- Ubuntu Desktop LTS
- Oracle VirtualBox
- Bash Terminal

---

## Skills Practiced

- Verifying current users and directories
- Analyzing Linux file ownership
- Understanding file permission concepts
- Modifying permissions with `chmod`
- Using `sudo` for administrative tasks

---

## Linux Commands Used

| Command                              | Purpose                                              |
| ------------------------------------ | ---------------------------------------------------- |
| `id`                                 | Display user ID and group membership                  |
| `ls -l`                              | List files with detailed permissions                 |
| `chmod`                              | Change file permissions                              |
| `chown`                              | Change file ownership                                |
| `sudo`                               | Execute command as superuser                         |
| `pwd`                                | Show current directory                               |

---

## Lab Activities

- Verified current users and directories using `id` and `pwd`.
- Analyzed file ownership by listing files with `ls -l`.
- Created a practice file to experiment with permission changes.
- Modified file permissions with `chmod` to test different access levels.
- Used `sudo` to perform administrative tasks on system files.
- Examined how ownership changes impacted access rights.

---

## Screenshots

### 01 – Verifying Current Users and Directory
![Verifying Current Users and Directory](01%20Verifying%20Current%20Users%20and%20Directory.png)
-
-### 02 – Analyzing Linux File Ownership
![Analyzing Linux File Ownership](02%20Analyzing%20Linux%20File%20Ownership.png)

### 03 – Understanding Linux File Permissions
![Understanding Linux File Permissions](03%20Understanding%20Linux%20File%20Permissions.png)
-
-### 04 – Creating a Practice File
![Creating a Practice File](04%20Mission4.txt.png)

### 05 – Modifying Linux File Permissions with chmod
![Modifying Linux File Permissions with chmod](05%20Modifying%20Linux%20File%20Permissions%20With%20chmod.png)
-
-### 06 – Examining Linux File Ownership
- ![Examining Linux File Ownership](06%20Examining%20Linux%20File%20Ownership.png)

- ### 07 – Using sudo for Administrative Tasks
![Using sudo for Administrative Tasks](07%20Using%20sudo%20for%20Administrative%20Tasks.png)

---

## Lessons Learned

- I learned how to read Linux permission strings and understand what access each user group has.
- I practiced using `chmod` to adjust file permissions and observed how those changes affect who can read, write, or execute files.
- I became more confident using `sudo` to carry out administrative tasks on files that require elevated privileges.
- Understanding file ownership and permissions is crucial for securing Linux environments and ensuring only authorized users have appropriate access.

---

## SOC Analyst Takeaways

- As a SOC analyst, knowing how permissions work helps when reviewing system logs and ensuring that sensitive files are protected.
- Regularly verifying file ownership and permission settings is a good practice to prevent unauthorized access or accidental modifications.
- Linux file permissions are a core element of system security, and mastering them is key to maintaining a secure operating environment.
