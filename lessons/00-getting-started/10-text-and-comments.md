# 0.10 Text, quotes and comments

[← Module 0 contents](README.md)

**Goal:** Change visible output and write notes that the computer ignores.

## Text inside quotation marks

A **string literal** is text between double quotes. A semicolon *after* the closing parenthesis ends the statement.

```c
#include <stdio.h>

int main(void)
{
    puts("READY");
    puts("PLAYER ONE");
    return 0;
}
```

**Expected output:**

```text
READY
PLAYER ONE
```

Each `puts` prints a new line.

## Comments

A **comment** is a note in the source that does not execute:

```c
// Display a welcome message.
puts("WELCOME");

/* This comment can
   occupy more than one line. */
```

This fragment belongs **inside `main`**, not in a new file on its own. The compiler ignores comments.

## Activity

Replace the two messages in your working `hello.c` with the example above. Add a `//` comment above each `puts` explaining what it displays. Compile and run.

Then deliberately change only the text inside quotes. Confirm that comments do not appear on the screen.

## Check yourself

- What happens when you put two `puts` calls one after another?
- Do comments produce output?
- Which kind of quotes surround text in C?

**Troubleshooting:** An unmatched quote may generate several compiler diagnostics. Check the *first* error location before changing anything else.

### Previous lessons used
- [0.09 Understand the shape of a C program](09-explain-main.md): function body and statements.
- [0.08 Compile and run Hello World](08-compile-and-run.md): compile and rerun.

[← Previous](09-explain-main.md) · [Next →](11-errors-and-debugging.md)
