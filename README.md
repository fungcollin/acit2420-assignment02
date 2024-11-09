# ACIT-2420 - Assignment 02

## Introduction

This repository contains two Bash Project scripts to prepare and admin a LINUX environment:

1. System Setup
2. New User Creation 

The first project's objective is to automate a system setup and sync.
The second project's objective is to provide user management properties. 

---

## Table of Contents

- [Project 1 - System Setup](#project-1-system-setup)
    - [Installing Packages](#script-1-1-installation---installing-packages)
    - [Creating Symbolic Links](#script-1-2-link---creating-symbolic-links)
    - [Setup Environment](#script-1-3-execute---setup-environment)
- [Project 2 - New User Creation](#project-2-new-user-creation)
    - [New-User Script](#script-2-1-new-user)

---

### Project 1: System Setup

---

#### Script 1-1: Installation - Installing Packages

This script installs packages listed in ```bash /home/<user>/packages```

> [!NOTE]
> You can add additional required packages in the packages file

---

#### Script 1-2: Link - Creating Symbolic Links

This script links configuration files from a designated Git repository to the system's configuration directory.

---

#### Script 1-3: Execute - Setup Environment

This script embeds the execution of the prior two scripts to setup the environment. 

> [!IMPORTANT]
> Run the execution script with the below command:
> ```bash
> sudo ./execute
> ```

---

### Project 2: New User Creation

#### Script 2-1: new-user

This script allows:
- User Creation
- Shell Configuration
- Home Directory Creation
- Group Addition

> [!IMPORTANT]
> A sample user creation script:
> ```bash
> sudo ./new-user -u Collin -s /bin/test -g "ACIT 2420"

Thank you for viewing this tutorial on setting up an environment and maintaining user management!

---

## References
1. ArchWiki. (2024, October 10). Pacman. ArchWiki. Retrieved November 8, 2024, from https://wiki.archlinux.org/title/Pacman
2. Baeldung. (n.d.). Username & user id in Linux. Baeldung. Retrieved November 8, 2024, from https://www.baeldung.com/linux/username-user-id
3. GeeksforGeeks. (2021, December 27). Random shell variable in Linux with examples. GeeksforGeeks. Retrieved November 8, 2024, from https://www.geeksforgeeks.org/random-shell-variable-in-linux-with-examples/
4. GNU. (n.d.). Bash manual. GNU. Retrieved November 8, 2024, from https://www.gnu.org/software/bash/manual/bash.html
5. HackTricks. (2024, October 23). EUID, RUID, and SUID for privilege escalation. HackTricks. Retrieved November 8, 2024, from https://book.hacktricks.xyz/linux-hardening/privilege-escalation/euid-ruid-suid
6. LinuxCommand.org. (n.d.). Sudo manual. LinuxCommand.org. Retrieved November 8, 2024, from https://linuxcommand.org/lc3_man_pages/sudo8.html
7. Man7.org. (n.d.). Group - Linux manual page. Retrieved November 8, 2024, from https://www.man7.org/linux/man-pages/man5/group.5.html
8. SS64. (n.d.). Bash Syntax File Operators. SS64. Retrieved November 8, 2024, from https://ss64.com/bash/syntax-file-operators.html
9. SS64. (n.d.). Bash ln command. SS64. Retrieved November 8, 2024, from https://ss64.com/bash/ln.html
10. SS64. (n.d.). Symlink command. SS64. Retrieved November 8, 2024, from https://ss64.com/bash/symlink.html
11. Tutorialspoint. (n.d.). Guide to generate random numbers in Linux. Retrieved November 8, 2024, from https://www.tutorialspoint.com/guide-to-generate-random-numbers-in-linux
12. Unix Stack Exchange. (2017, June 12). sed to change user id in /etc/passwd to zero. Stack Exchange. Retrieved November 8, 2024, from https://unix.stackexchange.com/questions/397236/sed-to-change-userid-in-etc-passwd-to-zero

> [!NOTE]
> References are avaliable within each script to further explain usage. 