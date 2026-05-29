# Networking in Linux
This section contains Linux networking concepts and commands commonly used in DevOps and SRE.

## Topics Covered
- Network Basics
- IP Address
- Hostname
- DNS
- Connectivity Checks
- Port Verification
- Network Troubleshooting
- HTTP Requests

## Commands
ping
curl
wget
ifconfig
ip addr
netstat
ss
nslookup
dig
traceroute
hostname

## Purpose
Networking knowledge is very important for DevOps and SRE engineers to troubleshoot connectivity issues, verify 
application communication, check ports and services, diagnose DNS problems, and maintain reliable production environments.
********************************************************************************************************************

# Networking in Linux

Linux networking commands are used to check connectivity, troubleshoot network issues, verify ports, and manage communication between systems.

Networking knowledge is very important in DevOps and Site Reliability Engineering (SRE) for diagnosing server communication issues, DNS problems, API connectivity, and production incidents.

# Common Networking Commands
**ping**
Checks network connectivity between systems.
ping google.com

**curl**
Transfers data from servers and tests APIs or websites.
curl google.com

**wget**
Downloads files from internet.
wget URL

**hostname**
Displays system hostname.
hostname

**ifconfig**
Displays network interface information.
ifconfig

**ip addr**
Displays IP address information.
ip addr

**netstat**
Displays network connections and ports.
netstat -tulnp

**ss**
Displays socket statistics and listening ports.
ss -tulnp

**nslookup**
Checks DNS resolution.
nslookup google.com

**dig**
Performs DNS lookup and troubleshooting.
dig google.com

# Why Networking is Important for DevOps/SRE

- Troubleshooting connectivity issues
- Checking application communication
- Verifying open ports
- Diagnosing DNS issues
- Monitoring network traffic
- Resolving production incidents
