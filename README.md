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

```bash
script here
```

> [!IMPORTANT]
> A sample user creation script:
> ```bash
> sudo ./new-user -u Collin -s /bin/test -g "ACIT 2420"

Thank you for viewing this tutorial on setting up an environment and maintaining user management!

---

# References
> [!IMPORTANT]
> References are avaliable within each script to cross reference the usage. 