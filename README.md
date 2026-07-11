# Project 4 – Linux Users & Permissions

## Objective

* Develop practical Linux access control skills used by Security Operations Center (SOC) analysts by viewing, interpreting, and modifying Linux file ownership and permissions within an Ubuntu virtual machine.

---

## Environment

* Ubuntu Desktop LTS
* Oracle VirtualBox
* Bash Terminal

---

## Skills Practiced

* Identifying Linux users
* Viewing the current working directory
* Examining Linux file ownership
* Interpreting Linux file permissions
* Creating files using `touch`
* Modifying file permissions using `chmod`
* Understanding file ownership using `chown`
* Using `sudo` for administrative tasks
* Applying the Principle of Least Privilege

---

## Linux Commands Used

| Command                              | Purpose                                       |
| ------------------------------------ | --------------------------------------------- |
| `whoami`                             | Display the current logged-in user            |
| `pwd`                                | Display the current working directory         |
| `ls -l`                              | Display file ownership and permissions        |
| `ls -la`                             | Display all files, including hidden files     |
| `touch mission4.txt`                 | Create a new file                             |
| `chmod a-w mission4.txt`             | Remove write permissions from all users       |
| `chmod u+x mission4.txt`             | Add execute permission for the file owner     |
| `sudo touch /tmp/mission4-admin.txt` | Create a file using administrative privileges |

---

## Lab Activities

* Verified the current Linux user account.
* Verified the current working directory.
* Examined Linux file ownership and permissions.
* Identified Owner, Group, and Others permission assignments.
* Created a practice file for permission testing.
* Modified file permissions using the `chmod` command.
* Reviewed file ownership using the `ls -l` command.
* Used `sudo` to perform an administrative task.
* Applied the Principle of Least Privilege to Linux access control.
* Reviewed a simulated file permission scenario to identify potential security risks.

---

## Screenshots

* P4 01 Verifying Current User and Working Directory
* P4 02 Viewing File Ownership
* P4 03 Understanding Linux File Permissions
* P4 04 Creating a Practice File
* P4 05 Modifying File Permissions with chmod
* P4 06 Reviewing File Ownership
* P4 07 Using sudo for Administrative Tasks

---

## Lessons Learned

* I learned how Linux controls access to files through users, groups, ownership, and permissions.
* I practiced using `chmod` to modify file permissions and verified the changes using the `ls -l` command.
* I learned how administrative privileges are temporarily granted using `sudo`.
* I learned that applying the Principle of Least Privilege helps reduce unnecessary security risks.

---

## SOC Analyst Takeaways

* File ownership and permissions are important indicators during Linux security investigations.
* Reviewing file permissions helps identify unauthorized access and potential privilege escalation.
* Applying the Principle of Least Privilege helps reduce the attack surface and strengthens overall system security.
