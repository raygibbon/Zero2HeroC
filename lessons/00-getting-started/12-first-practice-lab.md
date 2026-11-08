# 0.12 Practice lab: Your first game title screen

[← Module 0 contents](README.md)

**Goal:** Build a tiny text-based game welcome screen using *only* concepts already introduced.

This is a practice lab, not a new language lesson. You already know `main`, `puts`, string literals, comments, and how to compile.

## Your challenge

Without copying an entire finished program, create `title.c` in a new `title` folder beside `hello`.

Your program must:

1. Print an original game title.
2. Print a line of `================` underneath.
3. Print `PRESS START` on the next line.
4. Use at least one comment that describes what the program displays.
5. End with `return 0;`.

You can call `puts` more than once. You do **not** need to accept keyboard input yet, so `PRESS START` is only a message.

## Build

From the folder containing `title.c`:

```sh
gcc -std=c17 -Wall -Wextra -pedantic title.c -o title
```

If your system uses Clang, substitute `clang`. Run the output using the steps from 0.08.

## Test it

- Does it compile with no unexpected warnings?
- Are the three lines in the correct order?
- Can you change the title and rebuild it?
- Can you explain every character of the program at a beginner's level?

## Graduation

You have written, compiled, debugged and modified a C program. You have **not yet learned variables, conditions or loops**. Those come next. Keep `hello.c`, `title.c` and your notes as proof of your first working C code.

### Previous lessons used
- [0.07 Create your first C file](07-first-c-file.md): source file.
- [0.08 Compile and run Hello World](08-compile-and-run.md): build and launch.
- [0.09 Understand the shape of a C program](09-explain-main.md): program structure.
- [0.10 Text, quotes and comments](10-text-and-comments.md): output and comments.
- [0.11 Make mistakes on purpose](11-errors-and-debugging.md): troubleshooting.

[← Previous](11-errors-and-debugging.md) · [← Module 0 contents](README.md)
