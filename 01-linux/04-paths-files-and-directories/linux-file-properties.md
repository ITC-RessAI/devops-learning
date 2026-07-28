# Linux File Properties

## Overview
**Linux File Properties** covers the metadata attached to every file: permissions, ownership, size, and timestamps. This information is what `ls -l` displays, and it's the foundation for understanding permissions and ownership later in the course.

---

## Key Learnings
- `ls -l` shows permissions, owner, group, size, and modification date
- File type is shown by the first character (`-` file, `d` directory, `l` link)
- Timestamps track when a file was last modified or accessed
- File size is shown in bytes by default (`-h` for human-readable)

---

## Commands Practised
### `ls -l`
Displays detailed file information in long-listing format.

### `ls -lh`
Same as above, with human-readable file sizes.

### `stat`
Shows detailed metadata about a file, including access, modify, and change timestamps.

---

## Reflection
`ls -l` became second nature quickly, but `stat` showed me there's more metadata tracked per file than I expected.
