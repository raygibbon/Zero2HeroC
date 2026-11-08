# 0.03 What does a compiler do?

[← Module 0 contents](README.md)

**Goal:** Understand the journey from C source code to a program you can run.

## Three stages

```text
hello.c  →  C compiler  →  executable  →  running program
```

You write `hello.c`. The compiler reads the C source, checks it and produces a runnable file (normally with help from a *linker*). When you launch that executable, your operating system starts the program.

We will use **GCC** or **Clang**, common C compilers. They aren't programming languages. They are tools for compiling C.

## What can go wrong?

- **Compile-time error:** the compiler cannot build the program. For example, C syntax may be invalid.
- **Runtime error:** the program builds but fails when you execute it.
- **Logic error:** the program runs, but behaves incorrectly because your instructions are wrong.

A successful compile does *not* prove a game is correct.

## Activity

Draw the four boxes shown above on paper. Label which box is editable by you and which box is run by the computer.

## Check yourself

- Is the compiler the same as the editor?
- If the compiler reports an error, has your game started running?
- Why might a successfully compiled game still contain a bug?

### Previous lessons used
- [0.01 What is a program?](01-what-is-a-program.md): executable instructions.
- [0.02 What is source code?](02-source-code.md): editable C source files.

[← Previous](02-source-code.md) · [Next →](04-files-and-folders.md)
