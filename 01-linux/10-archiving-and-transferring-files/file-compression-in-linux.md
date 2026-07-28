# File Compression in Linux

## Overview
**File compression** reduces file size using tools like `gzip`, `bzip2`, and `xz`. Combined with `tar`, this produces the familiar `.tar.gz` archives commonly used for backups and software distribution.

---

## Key Learnings
- `gzip` is fast and widely supported; `xz` compresses more but is slower
- `tar` can compress and archive in a single command using flags like `-z` (gzip) or `-J` (xz)
- Compressed files typically end in `.gz`, `.bz2`, or `.xz`
- Decompression tools mirror the compression tool used to create the file

---

## Commands Practised
### `tar -czvf archive.tar.gz directory/`
Creates a compressed archive using gzip.

### `gzip file`
Compresses a single file, replacing it with a `.gz` version.

### `tar -xzvf archive.tar.gz`
Extracts a gzip-compressed tar archive.

---

## Reflection
Comparing archive sizes before and after compression made the practical benefit obvious — this is exactly what I'd use for backups going forward.
