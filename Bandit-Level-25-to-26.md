# Bandit Level 25 → Level 26

## What I did
I escaped from a restricted shell by modifying terminal behavior.

## Commands I used
ssh bandit25@bandit.labs.overthewire.org -p 2220
v
:set shell=/bin/bash
:shell

## Result
I accessed the next level.

## What I learned
- Escaping restricted shells
- Using vi to spawn a shell
