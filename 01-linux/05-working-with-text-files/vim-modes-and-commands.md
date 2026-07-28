# Vim Modes and Commands

## Overview
Vim operates through distinct **modes**: **Normal mode** for navigation and commands, **Insert mode** for typing text, and **Command mode** for saving, quitting, and searching. Switching between them deliberately is what makes Vim fast once it's familiar.

---

## Key Learnings
- `i` enters Insert mode from Normal mode
- `Esc` returns to Normal mode from any other mode
- `:` enters Command mode, used for saving, quitting, and search/replace
- Navigation in Normal mode (`h`, `j`, `k`, `l`) doesn't require arrow keys

---

## Commands Practised
### `i` – Insert Mode
Starts typing text at the cursor position.

### `Esc` – Return to Normal Mode
Exits Insert or Command mode back to Normal mode.

### `dd` – Delete Line
Deletes the current line in Normal mode.

### `:%s/old/new/g`
Finds and replaces text throughout the file.

---

## Reflection
Once the mode-switching became muscle memory, editing in Vim actually got faster than a mouse-driven editor for quick server-side edits.
