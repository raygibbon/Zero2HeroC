# 0.11 Make mistakes on purpose

[← Module 0 contents](README.md)

**Goal:** Become comfortable reading compiler errors instead of guessing.

## Experiment A: remove a semicolon

Start with your working `hello.c`. Remove the semicolon after `puts("READY")`. Save and compile.

**Expected:** compilation fails with a diagnostic near the missing punctuation (wording varies by compiler). Restore the semicolon and compile again.

## Experiment B: misspell a function name

Change `puts` to `putz`. Compile.

**Expected:** a diagnostic about an undeclared/unknown function or a similar error, depending on compiler and platform. Restore `puts`.

## Experiment C: a logic mistake

Change the message to `GOODBYE` even though you intended `READY`.

**Expected:** this compiles successfully but shows the wrong message. The compiler cannot know your intention.

## Record what happened

Write in `readme.txt`:

```text
Change I made:
What the compiler said:
What I expected:
How I fixed it:
```

Never assume the compiler's wording will be identical on every system.

## Check yourself

- What's the difference between a compiler error and a logic error?
- Why should you fix the first reported error before later ones?
- Can a program be wrong even if there are no warnings?

**Troubleshooting:** If compilation fails, an *old* executable may still exist. Do not mistake its output for a new successful build.

### Previous lessons used
- [0.03 What does a compiler do?](03-compilers.md): kinds of errors.
- [0.08 Compile and run Hello World](08-compile-and-run.md): compiler flags.
- [0.10 Text, quotes and comments](10-text-and-comments.md): working example.

[← Previous](10-text-and-comments.md) · [Next →](12-first-practice-lab.md)
