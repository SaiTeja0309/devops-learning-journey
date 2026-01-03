# Day 02 – Linux Basics for DevOps 🐧

## Why Linux for DevOps?
Linux is the backbone of most DevOps environments.  
Most servers 🖥️, containers 📦, and cloud instances ☁️ run on Linux 🐧, making it essential for automation 🤖, monitoring 📊, and troubleshooting 🔍.

---

## Basic Navigation Commands 

| Command | Description |
|-------|-------------|
| `pwd` | Show current directory |
| `ls` | List files and directories |
| `cd` | Change directory |

---

## File & Directory Operations

| Command | Description |
|-------|-------------|
| `touch file.txt` | Create a file |
| `mkdir dir` | Create a directory |
| `cp source dest` | Copy files |
| `mv source dest` | Move or rename files |
| `rm file` | Remove file |
| `rm -r dir` | Remove directory |

---

## File Permissions

Linux permissions are represented as:
r = read
w = write
x = execute

Example:
'''bash
-rwxr-xr--

| Entity  | Permission |
|-------- |------------|
| 'Owner' | rwx        |
| 'Group' | r-x        |
| 'User'  | r--        |


Change Permissions:

chmod 755 file.sh


**Why Permissions Matter in DevOps ?**

- Secure deployment scripts
- Prevent unauthorized access
- Control execution of automation scripts
- Essential for CI/CD pipelines


---


## Key Takeaways

- Linux knowledge is **non-negotiable** for DevOps

- CLI confidence improves troubleshooting speed

- Permissions play a big role in security & automation


📅 **Day 03:** Git - GitHub DevOps
