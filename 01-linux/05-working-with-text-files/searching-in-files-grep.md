# Searching in Files: grep

## Overview
**grep** searches text using pattern matching, including regular expressions. It's one of the most-used tools in Linux for finding specific lines inside files, logs, or command output.

---

## Key Learnings
- `grep` searches line by line and prints matching lines
- Combined with pipes, `grep` can filter the output of other commands
- Flags like `-i` (ignore case), `-r` (recursive), and `-n` (line numbers) extend its usefulness
- Basic regular expressions make searches far more flexible than plain text matching

---

## Commands Practised
### `grep "pattern" file`
Searches a file for lines matching the given pattern.

### `grep -r "pattern" directory`
Searches recursively through all files in a directory.

### `grep -in "pattern" file`
Case-insensitive search that also shows line numbers.

### `command | grep "pattern"`
Filters the output of another command using a pipe.

---

## Reflection
`grep` piped with other commands turned out to be one of the most practical tools in this whole course — I use it constantly to cut through noisy output.
