# 0.09 Understand the shape of a C program

[← Module 0 contents](README.md)

**Goal:** Recognise the parts of the Hello World program without needing to master functions yet.

## Read the code slowly

```c
#include <stdio.h>

int main(void)
{
    puts("Hello, game programmer!");
    return 0;
}
```

- `#include <stdio.h>` tells the preprocessor to include declarations from the standard input/output library. We need that declaration for `puts`.
- `int main(void)` defines the function where this example begins running. `int` means it returns an integer result; `void` means it accepts no arguments in this form.
- `{` and `}` enclose the function's body.
- `puts("Hello, game programmer!");` prints the message and a newline.
- `return 0;` reports successful completion to the calling environment.

**A function** is a named piece of code that can carry out work. We will study functions properly much later; for now, recognise `main` as our program's starting point.

## Why all the punctuation?

C uses symbols to separate parts of its grammar. The final semicolon marks the end of each of the two statements inside the function. Parentheses identify calls and function parameters; quotation marks surround literal text.

## Activity

On paper, point to: the header name, the function name, the string literal and the two statements inside the braces. Then change only the string, rebuild and run.

## Check yourself

- Which part is the text that gets printed?
- Why did we include `stdio.h`?
- Is `main` just another word for `puts`?

### Previous lessons used
- [0.07 Create your first C file](07-first-c-file.md): original code.
- [0.08 Compile and run Hello World](08-compile-and-run.md): running it.

[← Previous](08-compile-and-run.md) · [Next →](10-text-and-comments.md)
