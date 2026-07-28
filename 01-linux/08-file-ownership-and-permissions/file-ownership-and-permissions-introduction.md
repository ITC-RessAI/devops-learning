# File Ownership and Permissions Introduction

## Overview
Every file and directory in Linux has an **owner**, a **group**, and a set of **permissions** controlling who can read, write, or execute it. This model is the foundation of Linux security — access is decided per-file, per-user, and per-group.

---

## Key Learnings
- Every file has an owning user and an owning group
- Permissions are split into three categories: owner, group, and others
- Each category can have read (r), write (w), and execute (x) permissions
- `ls -l` shows this permission set as the first column of output

---

## Reflection
Seeing the permission string in `ls -l` broken into owner/group/other made a previously cryptic-looking output completely readable.
