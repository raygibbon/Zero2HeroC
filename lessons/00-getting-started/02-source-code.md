# 0.02 What is source code?

[← Module 0 contents](README.md)

**Goal:** Understand how a plain text file can contain the instructions for a program.

## Text a human can read

**Source code** is the text a programmer writes. Different programming languages have different rules for writing it. We will learn **C**. The compiler needs those rules to interpret our instructions.

Look at this tiny C statement:

```c
puts("Hello!");
```

You do not need to understand it yet. Notice that the instructions are text, but they contain characters that matter: parentheses, quotes and a semicolon. C is generally case-sensitive: `puts` and `PUTS` are not interchangeable.

## Source files

A C source file normally ends in `.c`, for example `hello.c`. The extension is part of the file name, not a command. You can open a `.c` file in a text editor.

**Text editor:** lets you write source code.

**Compiler:** processes the source code and creates the machine instructions that can run.

**Executable:** the result you can launch. It is different from your editable `.c` file.

## Activity

Create a folder called `zero2heroc-practice`. Inside it create a plain-text file called `notes.txt` and write three instructions for a game. Save it and open it again. You are practising editing and saving text, not programming yet.

## Check yourself

- Why can't a computer simply run arbitrary English instructions?
- What is the difference between `hello.c` and a compiled executable?
- Why should we avoid a word processor for writing C files?

### Previous lessons used
- [0.01 What is a program?](01-what-is-a-program.md): instructions and what a program does.

[← Previous](01-what-is-a-program.md) · [Next →](03-compilers.md)
