# Linux Permissions

This section contains Linux file and directory permissions concepts commonly used in DevOps and SRE.

## Topics Covered

- File Permissions
- Read, Write and Execute Permissions
- User, Group and Others
- chmod Command
- chown Command
- Permission Denied Issues
- File Ownership
- Sudo Access
- Real-time Permission Troubleshooting

## Commands
ls -l
chmod
chown
whoami
id
sudo

## Purpose

Understanding Linux permissions is very important for DevOps and SRE engineers because many production issues are 
related to access control, file ownership, script execution, and application permissions.
****************************************************************************************************************************
# Linux Permissions

Linux permissions are used to control access to files and directories in a system.

Permissions are very important in DevOps and Site Reliability Engineering (SRE) for security, access control, script execution, and troubleshooting production issues.

# Permission Types :
| Symbol | Meaning |
|--------|---------|
| r      | Read    |
| w      | Write   |
| x      | Execute |

# Permission Categories :
| Category  | Description   |
|-----------|---------------|
| User (u)  | Owner of file |
| Group (g) | Group members |
| Others (o)| Other users   |

# Common Permission Commands

**ls -l**
Displays file permissions and ownership.
ls -l

**chmod**
Changes file permissions.
chmod 755 demo.sh

**chown**
Changes file ownership.
sudo chown ubuntu:ubuntu demo.sh

**whoami**
Displays current user.
whoami

**id**
Displays user and group information.
id

**sudo**
Executes commands with elevated privileges.
sudo command_name

# Why Linux Permissions are Important for DevOps/SRE

- Securing servers and applications
- Controlling user access
- Managing script execution
- Preventing unauthorized changes
- Troubleshooting permission denied errors
- Managing production environments securely
