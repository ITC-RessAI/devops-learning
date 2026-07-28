# Standard Input and Output

## Overview
Linux treats input and output as **streams**: **stdin** (standard input, keyboard by default), **stdout** (standard output, terminal by default), and **stderr** (standard error, also the terminal by default but kept separate from stdout). Understanding these three streams is the foundation for redirection and piping.

---

## Key Learnings
- **stdin** (0) is where a program reads input from
- **stdout** (1) is where a program sends normal output
- **stderr** (2) is where a program sends error messages, separately from stdout
- Keeping stdout and stderr separate allows errors to be handled differently from normal output

---

## Reflection
Realising stdout and stderr are separate streams explained a lot of redirection behaviour that used to confuse me, like why errors still showed up on screen even when output was redirected to a file.
