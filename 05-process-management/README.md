# Process Management in Linux

This section contains Linux process management concepts commonly used in DevOps and SRE.

## Topics Covered

- What is a Process?
- Foreground and Background Processes
- Process Monitoring
- Process States
- Killing Processes
- CPU and Memory Usage
- Process Troubleshooting

## Commands
ps
ps -ef
top
htop
kill
killall
jobs
bg
fg

## Purpose
Process management is very important for DevOps and SRE engineers to monitor running applications, identify high CPU 
or memory usage, troubleshoot stuck services, and maintain system stability in production environments.
************************************************************************************************************************

# Process Management in Linux

A process is a running program or task in a Linux system.

Process management is very important in DevOps and Site Reliability Engineering (SRE) for monitoring applications, troubleshooting issues, managing system resources, and maintaining server stability.

# Common Process Management Commands
**ps**
Displays currently running processes.
ps

**ps -ef**
Displays detailed information about all running processes.
ps -ef

**top**
Displays real-time system processes and resource usage.
top

**htop**
Interactive process monitoring tool.
htop

**kill**
Terminates a process using Process ID (PID).
kill PID

**killall**
Terminates all processes by name.
killall process_name

**jobs**
Displays background jobs.
jobs

**bg**
Runs stopped job in background.
bg

**fg**
Brings background job to foreground.
fg

# Why Process Management is Important for DevOps/SRE

- Monitoring running applications
- Identifying high CPU or memory usage
- Troubleshooting stuck processes
- Managing production services
- Improving server performance
- Handling application failures
