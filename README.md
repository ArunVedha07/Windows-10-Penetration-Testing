# Windows 10 MS17-010 (EternalBlue) Exploitation

This repository documents the identification and exploitation of the MS17-010 (EternalBlue) vulnerability on a vulnerable Windows 10 system. The objective was to analyze SMB misconfigurations, confirm the vulnerability, and achieve remote code execution using Metasploit in a controlled lab environment.

## Summary of Actions
- Performed network and service enumeration using Nmap  
- Identified SMB service exposure on port 445  
- Confirmed MS17-010 vulnerability using NSE scripts  
- Exploited EternalBlue via Metasploit  
- Gained administrative shell access on the target system  

## Repository Structure
/screenshots — Evidence of each exploitation phase
/notes — Commands and observations
/report — Technical documentation

## Tools & Technologies
- Kali Linux  
- Nmap + NSE scripts  
- Metasploit Framework  
- VirtualBox lab environment  

## Purpose
This project was conducted strictly for educational purposes in an isolated and authorized lab environment.
