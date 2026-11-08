# 0.07 Create your first C file

[← Module 0 contents](README.md)

**Goal:** Create and save C source code. We will compile it in the next lesson.

## Type this yourself

Open your text editor. Create `hello.c` inside `zero2heroc-practice/module-00/hello/`.

```c
#include <stdio.h>

int main(void)
{
    puts("Hello, game programmer!");
    return 0;
}
```

Save the file. For now, **copy the punctuation exactly**. You are not expected to know what every line means: the following lessons explain each piece.

Make sure the file is actually called `hello.c`, rather than `hello.c.txt`.

## What you have made

You have created *source code*, not a running program. A few hints:

- `puts` asks to print text.
- The words in quotes are a **string literal**.
- The braces surround the body of the `main` function.

We will explore `#include`, `int`, `void` and `return` separately. Memorising them is not required yet.

## Activity

Close the editor and reopen `hello.c`. Compare every line with the example, including the semicolons.

## Check yourself

- Did saving the file create an executable?
- Is the file plain text?
- Which line contains the message you want displayed?

### Previous lessons used
- [0.02 What is source code?](02-source-code.md): writing source code.
- [0.04 Files, folders and extensions](04-files-and-folders.md): file paths.
- [0.06 Install a C compiler and editor](06-installing-tools.md): text editors.

[← Previous](06-installing-tools.md) · [Next →](08-compile-and-run.md)
