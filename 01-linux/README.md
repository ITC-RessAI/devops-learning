<img width="1000" height="538" alt="devops learning banner" src="./images/linux-banner.jpg" />

# Linux

![OS](https://img.shields.io/badge/OS-Linux-blue?logo=linux)
![Shell](https://img.shields.io/badge/Shell-Bash-blue?logo=gnubash)
![Shell](https://img.shields.io/badge/Shell-Zsh-blue?logo=gnubash)
![Focus](https://img.shields.io/badge/Focus-Linux%20Fundamentals-purple?logo=linux)
![Practice](https://img.shields.io/badge/Practice-Hands--on-orange)

This section documents my hands-on journey learning **Linux** — the first stop in my DevOps learning path.

Almost everything in DevOps sits on top of Linux. Containers, pipelines, cloud infrastructure, automation — none of it works without solid command-line fundamentals underneath.

So the goal here isn't to memorise commands. It's to actually understand how Linux behaves, so the concepts carry over cleanly.

---

## Learning Objectives

By working through this module, I aimed to:

- Confidently navigate the Linux file system via the command line
- Manage users, groups, and permissions
- Understand file ownership, special permissions, and links
- Work with text processing tools (`grep`, `vim`) and redirection
- Understand networking basics, DNS, and SSH
- Manage disks, partitions, file systems, and mounting
- Install software packages and manage services/daemons
- Apply everything through one consolidated hands-on lab per topic

---

## Topics Covered

### Introduction to Linux
An overview of what Linux is, why it dominates modern infrastructure, and why it's the starting point for the rest of the DevOps journey.

---

### The Linux Terminal and Manual

- [Linux Components](./03-linux-terminal-and-manual/linux-components.md)
Kernel, shell, and user space — the core building blocks of a Linux system.
- [Linux Command Structure](./03-linux-terminal-and-manual/linux-command-structure.md)
How a command is built: command, options, and arguments.
- [Getting Help](./03-linux-terminal-and-manual/getting-help.md)
Using `man` and `--help` to learn commands without leaving the terminal.

**Lab** — _to be added_

---

### Paths, Files, and Directories

- [File System Hierarchy Structure](./04-paths-files-and-directories/file-system-hierarchy-structure.md)
The standard Linux directory layout and what lives where.
- [Absolute vs Relative Path](./04-paths-files-and-directories/absolute-vs-relative-path.md)
The difference between a full path from root and a path relative to your current location.
- [Managing Files and Directories](./04-paths-files-and-directories/managing-files-and-directories.md)
Creating, copying, moving, and removing files and directories.
- [Linux File Properties](./04-paths-files-and-directories/linux-file-properties.md)
Reading file metadata: permissions, ownership, size, and timestamps.
- [Inode Number](./04-paths-files-and-directories/inode-number.md)
How Linux identifies files internally, separate from the filename.
- [Hard Link and Soft Link](./04-paths-files-and-directories/hard-link-and-soft-link.md)
The difference between a hard link (same inode) and a symbolic link (pointer to a path).

**Lab** — _to be added_

---

### Working with Text Files

- [Vim](./05-working-with-text-files/vim.md)
A modal text editor built for the terminal.
- [Vim Modes and Commands](./05-working-with-text-files/vim-modes-and-commands.md)
Normal, Insert, and Command mode, and how to move between them.
- [Searching in Files: grep](./05-working-with-text-files/searching-in-files-grep.md)
Pattern matching and searching text using regular expressions.

**Lab** — _to be added_

---

### Standard Input/Output and Redirection

- [Standard Input and Output](./06-standard-io-and-redirection/standard-input-and-output.md)
How Linux handles `stdin`, `stdout`, and `stderr` as data streams.
- [Redirection Overview](./06-standard-io-and-redirection/redirection-overview.md)
Sending output to a file or reading input from one (`>`, `>>`, `<`).
- [Piping in Linux](./06-standard-io-and-redirection/piping-in-linux.md)
Chaining commands together with `|` so one command's output becomes another's input.

**Lab** — _to be added_

---

### Users, Groups, and Permissions

- [UID (User Identifier)](./07-users-groups-and-permissions/uid-user-identifier.md)
The unique number Linux uses to identify a user internally.
- [Shadow File](./07-users-groups-and-permissions/shadow-file.md)
Where hashed passwords and account policies are stored.
- [Group File](./07-users-groups-and-permissions/group-file.md)
Where group membership is defined.
- [Sudo Command](./07-users-groups-and-permissions/sudo-command.md)
Running commands with elevated privileges, and how `sudo` differs from `su`.
- [Switching Users](./07-users-groups-and-permissions/switching-users.md)
Moving between user accounts on the same session.
- [Managing Users](./07-users-groups-and-permissions/managing-users.md)
Creating, modifying, and deleting user accounts.
- [User Passwords](./07-users-groups-and-permissions/user-passwords.md)
Setting passwords and managing password ageing policy.
- [Managing Groups](./07-users-groups-and-permissions/managing-groups.md)
Creating and modifying groups and group membership.

**Lab** — _to be added_

---

### File Ownership and Permissions

- [Introduction](./08-file-ownership-and-permissions/file-ownership-and-permissions-introduction.md)
The read/write/execute model and why permissions matter for security.
- [Changing File & Directory Permissions](./08-file-ownership-and-permissions/changing-file-and-directory-permissions.md)
Using `chmod` in symbolic and numeric (octal) modes.
- [File Ownership](./08-file-ownership-and-permissions/file-ownership.md)
Using `chown`/`chgrp` to change who owns a file.
- [Special Permissions Setuid](./08-file-ownership-and-permissions/special-permissions-setuid.md)
Running an executable with the permissions of its owner.
- [Special Permissions Setgid](./08-file-ownership-and-permissions/special-permissions-setgid.md)
Files and directories that inherit group ownership.
- [Special Permissions Sticky Bit](./08-file-ownership-and-permissions/special-permissions-sticky-bit.md)
Restricting deletion in shared directories to file owners only.

**Lab** — _to be added_

---

### Linux Networking

- [AWS Network Environment Setup](./09-linux-networking/aws-network-environment-setup.md)
Preparing a network environment on AWS to practice against.
- [Introduction to Networking](./09-linux-networking/introduction-to-networking.md)
Core networking concepts: IPs, interfaces, and how machines communicate.
- [Hostnamectl](./09-linux-networking/hostnamectl.md)
Viewing and setting a system's hostname.
- [Domain Name System (DNS)](./09-linux-networking/domain-name-system-dns.md)
How hostnames resolve to IP addresses.

**Lab** — _to be added_

---

### Archiving and Transferring Files (Backup)

- [Introduction to File Archiving](./10-archiving-and-transferring-files/introduction-to-file-archiving.md)
Bundling multiple files into one using `tar`.
- [File Compression in Linux](./10-archiving-and-transferring-files/file-compression-in-linux.md)
Reducing file size with tools like `gzip` and `xz`.
- [Copying & Transferring Files](./10-archiving-and-transferring-files/copying-and-transferring-files.md)
Moving files between systems using `scp` and `rsync`.

**Lab** — _to be added_

---

### Installing Software Packages

- [Introduction to RPM](./11-installing-software-packages/introduction-to-rpm.md)
The low-level package manager used on RHEL-based systems.
- [YUM](./11-installing-software-packages/yum.md)
The higher-level package manager that handles dependencies and repositories on top of RPM.

**Lab** — _to be added_

---

### Disk Management, Partitions, File System and Mounting

- [Disk Management Concepts](./12-disk-management-partitions-filesystem-mounting/disk-management-concepts.md)
How Linux represents and manages storage devices.
- [Disk Partitioning](./12-disk-management-partitions-filesystem-mounting/disk-partitioning.md)
Dividing a disk into separate, independently managed sections.
- [Disk Management Basic Commands](./12-disk-management-partitions-filesystem-mounting/disk-management-basic-commands.md)
Tools for inspecting disks and partitions.
- [Creating Disk Partitions](./12-disk-management-partitions-filesystem-mounting/creating-disk-partitions.md)
Building new partitions using `parted`, `fdisk`, and `gdisk`.
- [File System Concepts](./12-disk-management-partitions-filesystem-mounting/file-system-concepts.md)
How data is organized and stored on a partition.
- [Mounting in Linux](./12-disk-management-partitions-filesystem-mounting/mounting-in-linux.md)
Attaching a file system to the directory tree so it can be accessed.

**Lab** — _to be added_

---

### Daemons and Services

- [What are Daemons and Services?](./13-daemons-and-services/what-are-daemons-and-services.md)
Background processes that run without direct user interaction.
- [Managing Services in Linux](./13-daemons-and-services/managing-services-in-linux.md)
Starting, stopping, enabling, and checking service status with `systemctl`.

**Lab** — _to be added_

---

### Secure Shell (SSH)

- [SSH Overview](./14-secure-shell-ssh/ssh-overview.md)
Securely connecting to and managing remote systems.
- [Key-pair Authentication](./14-secure-shell-ssh/key-pair-authentication.md)
Using public/private key pairs instead of passwords to authenticate SSH sessions.

**Lab** — _to be added_

---

## Learning Approach

This repo reflects **how I learn**, not just what I learned:

- Hands-on practice in real Linux environments (AWS EC2, WSL)
- Understanding *why* commands work, not just memorising *what* they do
- One consolidated lab per main topic, combining all its subtopics into a single practical exercise
- Documenting the process so it's useful to my future self and to anyone starting out
