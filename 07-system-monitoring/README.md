# System Monitoring in Linux
This section contains Linux system monitoring concepts and commands commonly used in DevOps and SRE.

## Topics Covered
- CPU Monitoring
- Memory Monitoring
- Disk Usage Monitoring
- System Performance
- Running Services
- Resource Utilization
- Server Health Checks
- Performance Troubleshooting

## Commands
top
htop
free -m
df -h
du -sh
uptime
vmstat
iostat
sar
systemctl

## Purpose
System monitoring is very important for DevOps and SRE engineers to track server health, monitor CPU and memory usage, 
identify performance bottlenecks,troubleshoot production issues, and maintain application reliability.
**********************************************************************************************************************

# System Monitoring in Linux

System monitoring is used to track server health, CPU usage, memory usage, disk utilization, running services, and overall system performance.

System monitoring is one of the most important responsibilities in DevOps and Site Reliability Engineering (SRE) for maintaining production stability and troubleshooting incidents.

# Common System Monitoring Commands
**top**
Displays real-time CPU and memory usage.
top

**htop**
Interactive process monitoring tool.
htop

**free -m**
Displays memory usage in MB.
free -m

**df -h**
Displays disk space usage.
df -h

**du -sh**
Displays directory size.
du -sh directory_name

**uptime**
Displays server uptime and load average.
uptime

**vmstat**
Displays system performance statistics.
vmstat

**iostat**
Displays CPU and disk I/O statistics.
iostat

**sar**
Collects and displays system activity information.
sar

**systemctl**
Manages and checks system services.
systemctl status service_name

# Why System Monitoring is Important for DevOps/SRE

- Monitoring server health
- Detecting high CPU or memory usage
- Identifying disk space issues
- Troubleshooting production alerts
- Maintaining application reliability
- Preventing system failures
