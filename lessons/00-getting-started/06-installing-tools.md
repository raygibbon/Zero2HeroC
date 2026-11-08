# 0.06 Install a C compiler and editor

[← Module 0 contents](README.md)

**Goal:** Have a working C compiler and a plain text editor. SDL3 is not needed yet.

## Choose your operating system

**Debian/Ubuntu Linux:** open a terminal and run:

```sh
sudo apt update
sudo apt install build-essential
```

This installs GCC and common development tools. On systems using `doas`, follow their configured privilege-management method.

**Fedora Linux:**

```sh
sudo dnf install gcc make
```

**macOS:** install Apple's command-line tools:

```sh
xcode-select --install
```

**Windows:** install a GCC toolchain using **MSYS2** or use Visual Studio's C/C++ build tools. For MSYS2, follow the [official installer and UCRT64 instructions](https://www.msys2.org/); use the **UCRT64** terminal and install its GCC toolchain as documented there. Do not mix different MSYS2 terminal environments.

## Choose an editor

VS Code, Notepad++, Kate, or another plain-text editor is suitable. VS Code is an **editor**, not a compiler; installing it alone does not install GCC.

## Check the toolchain

Open the terminal associated with your compiler and run:

```sh
gcc --version
```

On macOS, `clang --version` is often the better check. A version message indicates the compiler command can be found.

## Activity

Record your operating system, editor, compiler name and version in `readme.txt`. Do not proceed until you can open the editor and run the compiler version command.

**Troubleshooting:** “Command not found” or “not recognized” means the executable isn't visible in that terminal. On Windows, ensure you used the terminal supplied with the chosen toolchain.

### Previous lessons used
- [0.03 What does a compiler do?](03-compilers.md): GCC and Clang.
- [0.05 Your first terminal commands](05-the-terminal.md): running commands.

[← Previous](05-the-terminal.md) · [Next →](07-first-c-file.md)
