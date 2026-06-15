# Linux Task 01: Linux Environment Setup & Essential Commands

## 📌 Project Overview
This repository contains the documentation and practical implementation for **Linux Task 01** of my Cyber Security Internship. The objective of this task is to establish a strong foundational understanding of the Linux operating system, master command-line interface (CLI) navigation, and practice fundamental file and directory management.

---

* **Name:** Khushi Gaikwad
* **Task:** Linux Task 01 - Environment Setup & Essential Commands
Cyber Security 
---

## 🛠️ Part A: Linux Installation & Verification
For this task, a Linux distribution was successfully set up inside a Virtual Machine (VM) environment. 

### Environment Details
* **OS Distribution:** Kali Linux
* **Hypervisor:** VMware Workstation / VirtualBox

### System Verification Screenshots
#### 1. Desktop Environment
![Desktop Environment](./desktop_environment.png)

#### 2. Terminal Window
![Terminal Window](./termina_window.png)

#### 3. System Information
![System Information](./part_e_system_info.png)

---

## 💻 Part B: Basic Navigation Commands
Below is the documentation for the essential navigation commands executed during this task.

| Command | Purpose |
| :--- | :--- |
| `pwd` | **Print Working Directory:** Displays the absolute path of the current directory you are in. |
| `ls` | **List:** Lists the files and directories inside the current working directory. |
| `ls -la` | **List Long & All:** Lists all files (including hidden ones starting with a `.`) with detailed attributes like permissions, size, and owner. |
| `cd` | **Change Directory:** Used to navigate between different folders/directories in the file system. |
| `clear` | **Clear Screen:** Clears all previous commands and outputs from the active terminal screen viewport. |
| `history` | **Command History:** Lists the sequence of commands previously executed in the terminal session. |
| `whoami` | **Who Am I:** Prints the username of the current active user logged into the shell. |
| `hostname` | **Host Name:** Displays the network name assigned to the local host/machine system. |

### Command Execution Screenshots
#### 1. Execution of pwd, ls, and ls -la
![Navigation Commands - Part 1](./part_b_navigation1.png)

#### 2. Execution of cd, clear, and history
![Navigation Commands - Part 2](./part_b_navigation2.png)

#### 3. Execution of whoami and hostname
![Navigation Commands - Part 3](./part_b_navigation3.png)

---

## 📁 Part C: Directory Management
Using the terminal, the following structured hierarchical laboratory environment was successfully created.

### Target Directory Structure
```text
Cybersecurity_Lab/
├── Networking
├── Linux
└── Cybersecurity
    ├── Ethicalhacking
    └── Reports

Verification
Commands Used: mkdir, cd, tree

Structure Screenshot:

📄 Part D: File Management
File operations including creation, moving, copying, renaming, and deletion were performed inside the newly created directory structure.

Detailed Operations Summary
File Creation: Used touch notes.txt, touch commands.txt, and touch report.txt.

Copying (cp): Copied files between directories to establish data redundancy.

Moving & Renaming (mv): Used mv to transfer files across directories and to rename files by specifying a new destination filename.

Deletion (rm): Used rm to safely clear temporary or redundant files from the lab directories.

File Operations Screenshot
📊 Part E: System Information Collection
The following snapshot details the exact system properties gathered from the running virtual machine environment.

Kernel Version: [Paste output of uname -a here]

Username: khushi [or your VM username]

Current Directory: [Paste your directory path here]

Current Date and Time: [Paste output of date here]

System Uptime: [Paste output of uptime here]

System Information Screenshot
Part F: Linux Research Activity
1. What is Linux?
Linux is an open-source, Unix-like operating system kernel first developed by Linus Torvalds in 1991. Unlike proprietary operating systems, the underlying source code of Linux is free to modify, distribute, and study. It serves as the core foundation for a massive variety of distributions that power everything from smartphones and personal desktops to enterprise cloud infrastructure and supercomputers.

2. Why is Linux important in Cyber Security?
Linux is paramount in Cyber Security because it offers total control over system operations, networking stacks, and user permissions. Its open-source nature allows developers and security analysts to inspect code for vulnerabilities, customize security kernels, and tightly audit processes. Furthermore, its lightweight modular structure makes it ideal for running persistent security appliances, firewalls, and lightweight container networks.

3. Difference between Linux and Windows
Source Model: Linux is open-source (free to customize and distribute), whereas Windows is a closed-source, proprietary operating system owned by Microsoft.

Interface & Paradigm: Linux is built around a CLI-first, file-centric philosophy (everything is a file). Windows relies heavily on a Graphical User Interface (GUI) and utilizes a registry system for configuration management.

File System: Linux uses case-sensitive structures like ext4 or Btrfs radiating from a root directory (/). Windows utilizes the case-insensitive NTFS system divided across independent drive letters (e.g., C:, D:).

Security & Permissions: Linux features a native, strict privilege model (Root vs User accounts) designed for multi-user safety, reducing its susceptibility to mainstream malware compared to consumer Windows environments.

4. What is a Linux Distribution?
Since Linux itself is strictly a kernel (the core engine that manages hardware communication), it requires software utilities to make it a usable operating system. A Linux Distribution (or "Distro") is a complete operating system package that bundles the Linux kernel with a desktop environment, package managers, system installers, configuration tools, and pre-installed user software applications. Examples include Ubuntu, Kali Linux, Fedora, and Debian.

5. Why do Ethical Hackers prefer Linux-based operating systems?
Ethical Hackers prefer Linux due to its native portability, granular hardware control, and extensive scripting support, which allows seamless task automation. Specialized security distributions like Kali Linux or Parrot OS come pre-packaged with thousands of built-in penetration testing, network sniffing, reverse engineering, and forensic tools. Additionally, Linux allows direct injection into wireless network cards and raw manipulation of network packets, which is highly restricted or impossible on standard commercial operating systems.

