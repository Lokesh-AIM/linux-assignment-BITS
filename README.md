# Linux System Administration Assignment

## Overview

This repository contains the solutions for the Linux System Administration graded assignment. The objective of this assignment is to demonstrate practical knowledge of Linux commands, file system management, permissions, file I/O, links, and storage management.

Each question has been organized into a separate folder containing:

- Command outputs
- Required report
- Supporting files created during execution
- Screenshots (where required)
- Brief observations and explanations

---

## Repository Structure

```
linux-assignment/
│
├── README.md
│
├── Q1_Environment_Verification/
│   ├── Environment_Report.txt
│   ├── Q1_Command_Output.txt
│   └── Screenshots/
│
├── Q2_Secure_Workspace/
│   ├── Project_Workspace_Report.txt
│   ├── Q2_Command_Output.txt
│   ├── project_workspace/
│   └── Screenshots/
│
├── Q3_Link_Analysis/
│   ├── Link_Analysis_Report.txt
│   ├── Q3_Command_Output.txt
│   ├── hardlink.txt
│   ├── symlink.txt
│   └── Screenshots/
│
├── Q4_IO_Investigation/
│   ├── IO_Investigation_Report.txt
│   ├── Q4_Command_Output.txt
│   ├── output.txt
│   ├── error.txt
│   ├── app.log
│   └── Screenshots/
│
└── Q5_Storage_Assessment/
    ├── Storage_Assessment_Report.txt
    ├── Q5_Command_Output.txt
    └── Screenshots/
```

---

# Question 1 – Linux Environment Verification

### Objective

Verify the Linux/macOS environment by collecting basic system and user information.

### Commands Used

- `whoami`
- `groups`
- `echo $SHELL`
- `pwd`
- `ls -la`
- `ping`

### Files Included

- Environment_Report.txt
- Q1_Command_Output.txt
- Screenshots

---

# Question 2 – Secure Project Workspace Setup

### Objective

Create a secure project workspace and configure appropriate file permissions.

### Commands Used

- `mkdir`
- `touch`
- `find`
- `chmod`
- `umask`
- `stat`
- `ls`
- `id`
- `whoami`

### Files Included

- Project_Workspace_Report.txt
- Q2_Command_Output.txt
- project_workspace/
- Screenshots

---

# Question 3 – File System and Link Analysis

### Objective

Understand the behavior of hard links and symbolic links.

### Commands Used

- `echo`
- `ln`
- `ln -s`
- `ls -li`
- `stat`
- `cat`
- `rm`

### Files Included

- Link_Analysis_Report.txt
- Q3_Command_Output.txt
- hardlink.txt
- symlink.txt
- Screenshots

---

# Question 4 – File Access and I/O Investigation

### Objective

Explore Linux file descriptors, file access, output redirection, error redirection, and resource limits.

### Commands Used

- `tail`
- `jobs`
- `ps`
- `lsof`
- `echo`
- `cat`
- `ulimit`
- `kill`

### Files Included

- IO_Investigation_Report.txt
- Q4_Command_Output.txt
- app.log
- output.txt
- error.txt
- Screenshots

---

# Question 5 – Storage Health Assessment

### Objective

Analyze storage devices, mounted file systems, disk usage, inode utilization, and overall storage health.

### Commands Used

(macOS equivalent commands were used where Linux commands were unavailable.)

- `diskutil list`
- `df -h`
- `df -i`
- `mount`
- `du`

### Files Included

- Storage_Assessment_Report.txt
- Q5_Command_Output.txt
- Screenshots

---

# Platform

The assignment was completed on:

- **Operating System:** macOS (Apple Silicon)
- **Terminal:** zsh
- **Architecture:** Apple M1

Since macOS is a Unix-based operating system, the majority of Linux commands work without modification. For Linux-specific commands such as `lsblk`, the appropriate macOS equivalent (`diskutil list`) was used.

---

# Learning Outcomes

Through this assignment, the following Linux concepts were practiced:

- User and group management
- Shell environment
- Directory navigation
- File permissions
- Ownership
- Umask
- Hard links
- Symbolic links
- Inodes
- File metadata
- File descriptors
- Standard input/output/error redirection
- Process management
- Storage devices
- Mounted file systems
- Disk usage
- Inode usage

---

# Author

**Lokesh Pathe**

Completed as part of the Linux System Administration Graded Assignment.

---
