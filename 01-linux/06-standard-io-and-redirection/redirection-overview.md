# Redirection Overview

## Overview
**Redirection** changes where a command's input comes from or where its output goes, using `>`, `>>`, and `<`. This makes it possible to save command output to a file, append to a log, or feed a file in as input, instead of relying on the terminal.

---

## Key Learnings
- `>` redirects output to a file, overwriting it
- `>>` redirects output to a file, appending instead of overwriting
- `<` redirects a file's content in as a command's input
- `2>` redirects stderr specifically, separate from stdout

---

## Commands Practised
### `command > file`
Writes a command's output to a file, replacing existing content.

### `command >> file`
Appends a command's output to the end of a file.

### `command 2> errors.log`
Redirects only error output to a separate log file.

---

## Reflection
Once I understood redirection was just pointing streams somewhere other than the terminal, chaining it with piping made a lot more sense.
