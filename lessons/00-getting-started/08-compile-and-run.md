# 0.08 Compile and run Hello World

[← Module 0 contents](README.md)

**Goal:** Turn `hello.c` into an executable and run it yourself.

## Start in the correct folder

Open a terminal and navigate to the folder containing `hello.c`. List the files to confirm the name.

## Build with GCC

On Linux, macOS (when GCC is available), or the MSYS2 UCRT64 terminal on Windows:

```sh
gcc -std=c17 -Wall -Wextra -pedantic hello.c -o hello
```

Here is each part:

- `gcc`: start the compiler.
- `-std=c17`: use the C17 language standard.
- `-Wall -Wextra -pedantic`: ask for useful warnings.
- `hello.c`: the source file to compile.
- `-o hello`: name the output executable `hello` (Windows normally adds `.exe`).

If your Mac has Clang but no `gcc`, replace `gcc` with `clang` in that command.

**A successful build may print nothing.** The executable should appear in the folder.

## Run it

On Linux/macOS:

```sh
./hello
```

On PowerShell:

```powershell
./hello.exe
```

On MSYS2 UCRT64, `./hello.exe` also works.

**Expected output:**

```text
Hello, game programmer!
```

## Activity

Run the program three times. Edit the message, save, compile again, then rerun it. Notice that changing source code alone does not change the previously built executable.

## Check yourself

- What does `-o` do?
- Why must you recompile after editing?
- What is the difference between `hello.c` and `hello.exe` (Windows) or `hello` (Linux)?

**Troubleshooting:** “No such file” usually means the terminal is in the wrong folder. A permission or launch issue means the executable didn't build or you are invoking the wrong file.

### Previous lessons used
- [0.03 What does a compiler do?](03-compilers.md): compilation.
- [0.05 Your first terminal commands](05-the-terminal.md): navigating.
- [0.07 Create your first C file](07-first-c-file.md): the source program.

[← Previous](07-first-c-file.md) · [Next →](09-explain-main.md)
