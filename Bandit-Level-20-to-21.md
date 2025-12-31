# Bandit Level 20 → Level 21

## What I did
I communicated over a local TCP port to retrieve the password.

## Commands I used
# Terminal 1
nc -l 1234

# Terminal 2
./suconnect 1234

## Result
I got the password for Level 21.

## What I learned
- Networking basics with netcat
- Sending and receiving data between processes
