# 0.05 Your first terminal commands

[← Module 0 contents](README.md)

**Goal:** Open a terminal, see which folder you are in and navigate without guessing.

## What is a terminal?

A terminal lets you type commands for your operating system. It is not where you write C programs. We use it to run the compiler and the executable.

Open **PowerShell** or **Windows Terminal** on Windows, or a terminal application on Linux/macOS.

### Show the current folder

On Linux/macOS:

```sh
pwd
```

In PowerShell:

```powershell
Get-Location
```

### List files

Linux/macOS: `ls`. PowerShell: `Get-ChildItem` (or `ls`).

### Change folders

Use `cd` followed by your folder path. Put paths containing spaces inside quotation marks.

```text
cd zero2heroc-practice
```

The command above works only if that folder is inside your current folder. If not, navigate from the correct parent folder or use the full path.

To go one folder up, type `cd ..`.

## Activity

Navigate into `module-00/hello`, list its contents and confirm that `readme.txt` is there. Go up one folder and then return.

## Check yourself

- How do you find your current directory?
- What does `cd ..` do?
- What is the difference between the terminal and a source editor?

**Troubleshooting:** A “path not found” error usually means your starting location or spelling is different. First check your current location and list its files.

### Previous lessons used
- [0.04 Files, folders and extensions](04-files-and-folders.md): directories and paths.

[← Previous](04-files-and-folders.md) · [Next →](06-installing-tools.md)
