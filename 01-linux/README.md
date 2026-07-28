# Linux

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
- [Linux Command Structure](./03-linux-terminal-and-manual/linux-command-structure.md)
- [Getting Help](./03-linux-terminal-and-manual/getting-help.md)

**Lab** — _to be added_

---

### Paths, Files, and Directories
- [File System Hierarchy Structure](./04-paths-files-and-directories/file-system-hierarchy-structure.md)
- [Absolute vs Relative Path](./04-paths-files-and-directories/absolute-vs-relative-path.md)
- [Managing Files and Directories](./04-paths-files-and-directories/managing-files-and-directories.md)
- [Linux File Properties](./04-paths-files-and-directories/linux-file-properties.md)
- [Inode Number](./04-paths-files-and-directories/inode-number.md)
- [Hard Link and Soft Link](./04-paths-files-and-directories/hard-link-and-soft-link.md)

**Lab** — _to be added_

---

### Working with Text Files
- [Vim](./05-working-with-text-files/vim.md)
- [Vim Modes and Commands](./05-working-with-text-files/vim-modes-and-commands.md)
- [Searching in Files: grep](./05-working-with-text-files/searching-in-files-grep.md)

**Lab** — _to be added_

---

### Standard Input/Output and Redirection
- [Standard Input and Output](./06-standard-io-and-redirection/standard-input-and-output.md)
- [Redirection Overview](./06-standard-io-and-redirection/redirection-overview.md)
- [Piping in Linux](./06-standard-io-and-redirection/piping-in-linux.md)

**Lab** — _to be added_

---

### Users, Groups, and Permissions
- [UID (User Identifier)](./07-users-groups-and-permissions/uid-user-identifier.md)
- [Shadow File](./07-users-groups-and-permissions/shadow-file.md)
- [Group File](./07-users-groups-and-permissions/group-file.md)
- [Sudo Command](./07-users-groups-and-permissions/sudo-command.md)
- [Switching Users](./07-users-groups-and-permissions/switching-users.md)
- [Managing Users](./07-users-groups-and-permissions/managing-users.md)
- [User Passwords](./07-users-groups-and-permissions/user-passwords.md)
- [Managing Groups](./07-users-groups-and-permissions/managing-groups.md)

**Lab** — _to be added_

---

### File Ownership and Permissions
- [Introduction](./08-file-ownership-and-permissions/file-ownership-and-permissions-introduction.md)
- [Changing File & Directory Permissions](./08-file-ownership-and-permissions/changing-file-and-directory-permissions.md)
- [File Ownership](./08-file-ownership-and-permissions/file-ownership.md)
- [Special Permissions — Setuid](./08-file-ownership-and-permissions/special-permissions-setuid.md)
- [Special Permissions — Setgid](./08-file-ownership-and-permissions/special-permissions-setgid.md)
- [Special Permissions — Sticky Bit](./08-file-ownership-and-permissions/special-permissions-sticky-bit.md)

**Lab** — _to be added_

---

### Linux Networking
- [AWS Network Environment Setup](./09-linux-networking/aws-network-environment-setup.md)
- [Introduction to Networking](./09-linux-networking/introduction-to-networking.md)
- [Hostnamectl](./09-linux-networking/hostnamectl.md)
- [Domain Name System (DNS)](./09-linux-networking/domain-name-system-dns.md)

**Lab** — _to be added_

---

### Archiving and Transferring Files (Backup)
- [Introduction to File Archiving](./10-archiving-and-transferring-files/introduction-to-file-archiving.md)
- [File Compression in Linux](./10-archiving-and-transferring-files/file-compression-in-linux.md)
- [Copying & Transferring Files](./10-archiving-and-transferring-files/copying-and-transferring-files.md)

**Lab** — _to be added_

---

### Installing Software Packages
- [Introduction to RPM](./11-installing-software-packages/introduction-to-rpm.md)
- [YUM](./11-installing-software-packages/yum.md)

**Lab** — _to be added_

---

### Disk Management, Partitions, File System and Mounting
- [Disk Management Concepts](./12-disk-management-partitions-filesystem-mounting/disk-management-concepts.md)
- [Disk Partitioning](./12-disk-management-partitions-filesystem-mounting/disk-partitioning.md)
- [Disk Management — Basic Commands](./12-disk-management-partitions-filesystem-mounting/disk-management-basic-commands.md)
- [Creating Disk Partitions](./12-disk-management-partitions-filesystem-mounting/creating-disk-partitions.md)
- [File System Concepts](./12-disk-management-partitions-filesystem-mounting/file-system-concepts.md)
- [Mounting in Linux](./12-disk-management-partitions-filesystem-mounting/mounting-in-linux.md)

**Lab** — _to be added_

---

### Daemons and Services
- [What are Daemons and Services?](./13-daemons-and-services/what-are-daemons-and-services.md)
- [Managing Services in Linux](./13-daemons-and-services/managing-services-in-linux.md)

**Lab** — _to be added_

---

### Secure Shell (SSH)
- [SSH Overview](./14-secure-shell-ssh/ssh-overview.md)
- [Key-pair Authentication](./14-secure-shell-ssh/key-pair-authentication.md)

**Lab** — _to be added_

---

## Learning Approach

This repo reflects **how I learn**, not just what I learned:

- Hands-on practice in real Linux environments (AWS EC2, WSL)
- Understanding *why* commands work, not just memorising *what* they do
- One consolidated lab per main topic, combining all its subtopics into a single practical exercise
- Documenting the process so it's useful to my future self and to anyone starting out
