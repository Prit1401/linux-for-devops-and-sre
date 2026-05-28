# User Management in Linux

This section contains Linux user and group management concepts commonly used in DevOps and Site Reliability Engineering (SRE).

Topics Covered:
- Users and Groups
- Root User
- Sudo Access
- User Permissions
- User Management Commands

Commands:
- whoami
- id
- who
- groups
- sudo
- useradd
- passwd

# User Management in Linux
Linux user management is used to create, manage, and control users and groups in a system.

User management is very important in DevOps and Site Reliability Engineering (SRE) for access control, permissions, security, and server administration.

# Common User Management Commands

**whoami**
Displays current logged-in user.
whoami

**id**
Displays user ID (UID), group ID (GID), and groups information.
id

**who**
Displays users currently logged into the system.
who

**groups**
Displays groups associated with current user.
groups

**sudo**
Executes commands with elevated/root privileges.
sudo command_name

**useradd**
Creates a new user.
sudo useradd demo-user

**passwd**
Sets or changes user password.
sudo passwd demo-user

# Why User Management is Important for DevOps/SRE

- Managing server access
- Controlling permissions
- Improving security
- Restricting unauthorized access
- Managing application users
- Supporting production environments securely
