# Bandit Level 16 → Level 17

## What I did
I scanned local ports to find the correct SSL service.

## Commands I used
nmap localhost -p 31000-32000
openssl s_client -connect localhost:31790

## Result
I got the password for Level 17.

## What I learned
- Port scanning with nmap
- Identifying services running on unknown ports
