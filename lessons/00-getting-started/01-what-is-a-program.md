# 0.01 What is a program?

[← Module 0 contents](README.md)

**Goal:** Explain what a computer program does without needing to write C yet.

## A program is a set of instructions

A computer follows precise instructions. A program is a collection of those instructions, written to accomplish a task. A game is a program: it reads controls, updates the game world and shows the result. A recipe is a useful analogy, but unlike a human cook, a computer cannot guess what you meant.

Consider a game character moving right:

1. Read which key is pressed.
2. If the right-arrow key is pressed, change the character's position.
3. Draw the character at that position.
4. Repeat.

This is a *description* of a program, not C code. We will learn how to express each step in C later.

## Program versus file

A **file** stores information. A **program** is instructions the computer can execute. The program you write will first be a text file containing *source code*. A compiler will turn it into an executable program.

## Activity: write an instruction sequence

On paper, describe how a game decides whether a player picked up a coin. Try writing at least four precise steps. What would happen if you forgot to update the score?

## Check yourself

- What makes a program different from an ordinary picture?
- Why does a computer need precise instructions?
- Can you describe one repeated task in a game?

**Troubleshooting:** There is nothing to install or run in this lesson. If a term is unfamiliar, write it down. We revisit each one.

### Previous lessons used
None. This is your starting point.

[Next: 0.02 What is source code? →](02-source-code.md)
