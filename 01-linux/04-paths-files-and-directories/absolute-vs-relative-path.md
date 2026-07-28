# Absolute vs Relative Path

## Overview
An **absolute path** always starts from the root directory `/` and points to a file or directory no matter where you currently are. A **relative path** is written relative to the current working directory, using shortcuts like `.` (current directory) and `..` (parent directory).

Understanding the difference avoids a lot of confusion when scripting or navigating unfamiliar systems.

---

## Key Learnings
- Absolute paths always start with `/` and are unambiguous
- Relative paths depend on the current working directory
- `.` refers to the current directory, `..` refers to the parent
- Relative paths are shorter but can break if run from the wrong location

---

## Commands Practised
### `pwd`
Prints the current working directory — the reference point for any relative path.

### `cd ..`
Moves up one directory using a relative path.

### `cd /`
Moves directly to the root using an absolute path.

---

## Reflection
I used to mix these up in scripts. Being deliberate about absolute vs relative paths now saves me from broken references later.
