# Bandit Level 12 → Level 13

## What I did
I converted a hex dump back to a file and extracted multiple compressed layers.

## Commands I used
xxd -r data.txt > data.bin
file data.bin
gzip -d
bzip2 -d
tar -xf

## Result
I got the password for Level 13.

## What I learned
- Handling hex dumps
- Working with compressed files
- Identifying file types
