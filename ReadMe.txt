# Task 1: Network Port Scanning using Nmap

## 🎯 Objective
Identify open ports and services running in the local network using a TCP SYN scan with Nmap.

## 🛠️ Tools Used
- Nmap
- Kali Linux (running in a VM)

## 🖧 IP Range Scanned
`192.168.81.157/24`

## 🔍 Nmap Command Used
```bash
nmap -sS 192.168.81.157/24 -oN First_scan.txt
