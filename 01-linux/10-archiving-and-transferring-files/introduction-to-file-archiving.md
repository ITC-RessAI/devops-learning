# Introduction to File Archiving

## Overview
**File archiving** bundles multiple files and directories into a single file using `tar`, making backups and transfers simpler. Archiving on its own doesn't reduce file size — it just packages files together, which is often combined with compression.

---

## Key Learnings
- `tar` bundles multiple files/directories into a single `.tar` archive
- Archiving preserves directory structure and file permissions
- Archives can be created, listed, and extracted with the same tool
- Archiving and compression are separate steps, often combined in one command

---

## Commands Practised
### `tar -cvf archive.tar directory/`
Creates a new archive from a directory.

### `tar -tvf archive.tar`
Lists the contents of an archive without extracting it.

### `tar -xvf archive.tar`
Extracts an archive's contents.

---

## Reflection
Once I separated "archiving" from "compressing" in my head, the different `tar` flag combinations stopped feeling arbitrary.
