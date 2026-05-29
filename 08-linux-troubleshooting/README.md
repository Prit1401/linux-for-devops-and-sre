# Linux Troubleshooting

This section contains common Linux troubleshooting concepts, commands, and real-world scenarios used in DevOps and SRE.

## Topics Covered

- High CPU Usage
- Memory Issues
- Disk Full Issues
- Service Down Troubleshooting
- Permission Denied Errors
- Process Troubleshooting
- Network Connectivity Issues
- Log Analysis
- Server Health Checks

## Commands

top
ps -ef
free -m
df -h
du -sh
systemctl status
journalctl
tail -f
netstat
ss
ping
curl

## Purpose
Linux troubleshooting is one of the most important skills for DevOps and SRE engineers to identify root causes,
resolve production issues, maintain system stability, and ensure application reliability in real-world environments.
********************************************************************************************************************

# Linux Troubleshooting

Linux troubleshooting is the process of identifying, analyzing, and resolving issues related to servers, applications, services, networking, permissions, and system performance.

Troubleshooting is one of the core responsibilities of DevOps and Site Reliability Engineering (SRE) teams in production environments.

# Common Troubleshooting Areas

- High CPU Usage
- Memory Issues
- Disk Full Issues
- Service Down Issues
- Permission Denied Errors
- Process Troubleshooting
- Network Connectivity Problems
- DNS Resolution Issues
- Application Failures
- Log Analysis

# Common Troubleshooting Commands
**top**
Checks CPU and memory usage.
top

**ps -ef**
Displays running processes.
ps -ef

**free -m**
Checks memory utilization.
free -m

**df -h**
Checks disk usage.
df -h

**du -sh**
Checks directory size.
du -sh directory_name

**systemctl status**
Checks service status.
systemctl status service_name

**journalctl**
Displays system logs.
journalctl

**tail -f**
Monitors logs in real time.
tail -f logfile.log

**ss -tulnp**
Checks listening ports and services.
ss -tulnp

**ping**
Checks connectivity.
ping google.com

**curl**
Tests APIs and website connectivity.
curl google.com


# Why Linux Troubleshooting is Important for DevOps/SRE
- Resolving production incidents
- Identifying root causes
- Maintaining application availability
- Improving server stability
- Monitoring system health
- Reducing downtime
