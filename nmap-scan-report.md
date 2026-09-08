# Nmap Network Scanning Lab

## Objective

To perform a network scan against a deliberately vulnerable lab machine and identify open ports, services, and basic operating system information.

## Target

- IP Address: 192.168.10.4
- Environment: Local cybersecurity lab

## Tool Used

- Nmap

## Command Used

nmap -T4 -A -p- -v 192.168.10.4

## Findings

The scan identified the following open TCP ports:

- 22/tcp — SSH
- 80/tcp — HTTP
- 111/tcp — RPCBind
- 139/tcp — NetBIOS/SMB
- 443/tcp — HTTPS
- 32768/tcp — RPC
- 32769/tcp — RPC

The scan also identified an older Linux 2.4.x operating system and Apache web services.

## Learning Outcome

This exercise helped me understand:

- How Nmap performs network reconnaissance
- How to identify open ports
- How to identify services running on a host
- How service enumeration can help security professionals assess attack surface
- The importance of documenting security findings

## Ethical Note

This scan was performed only against a deliberately configured machine in my own local cybersecurity lab for educational purposes.

