# SSH Brute Force Detection Lab

## Objective
Detect SSH brute-force attack via auth.log.

## Environment
- Ubuntu Server
- Kali Linux

## Attack
hydra -l user -P rockyou.txt ssh://IP

## Analyst Tasks
- Find attacker IP
- Count failed login attempts
- Determine attack time
