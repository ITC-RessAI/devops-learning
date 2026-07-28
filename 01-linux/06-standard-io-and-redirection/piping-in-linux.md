# Piping in Linux

## Overview
A **pipe** (`|`) connects the stdout of one command directly to the stdin of another, letting commands be chained together to build more powerful one-liners without writing intermediate files.

---

## Key Learnings
- `|` sends one command's output directly into the next command's input
- Multiple commands can be chained in a single pipeline
- Piping combines well with `grep`, `sort`, `wc`, and other filtering tools
- Each command in a pipeline runs independently but processes data as a stream

---

## Commands Practised
### `command1 | command2`
Feeds the output of `command1` directly into `command2`.

### `ls -l | grep ".txt"`
Lists files and filters for only `.txt` files.

### `cat file | wc -l`
Counts the number of lines in a file by piping it into `wc`.

---

## Reflection
Piping is where Linux commands started to feel less like isolated tools and more like a language I could combine to build exactly what I needed.
