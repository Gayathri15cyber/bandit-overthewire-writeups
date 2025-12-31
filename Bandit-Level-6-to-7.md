# Bandit Level 6 → Level 7

## What I did
I searched the system for a file owned by a specific user and group.

## Commands I used
find / -user bandit7 -group bandit6 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password

## Result
I got the password for Level 7.

## What I learned
- How to search files by user and group
- Redirecting error messages
