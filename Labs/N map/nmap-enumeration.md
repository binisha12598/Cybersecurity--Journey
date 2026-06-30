##Objective 
Learn how to discover hosts, open ports, and running services using Nmap.

# Nmap
Nmap (Network Mapper) is a network scanning tool used to discover hosts, identify open ports, detect running services, and gather information about a target network.

## Topics I Learned
- Host discovery
- TCP and UDP port scanning
- Service version detection
- Operating system detection
- Nmap Scripting Engine (NSE)

## Common Commands

nmap <target-ip>
nmap -sV <target-ip>
nmap -O <target-ip>
nmap -A <target-ip>
nmap -Pn <target-ip>

## What I Learned
- Different scan types provide different information.
- Service detection helps identify software versions.
- OS detection is based on TCP/IP fingerprinting.
- Enumeration is often the most important phase before exploitation.
