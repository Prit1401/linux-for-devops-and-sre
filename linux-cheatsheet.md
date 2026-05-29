Linux Cheat Sheet for DevOps & SRE:

| Command            | Purpose                            |
| ------------------ | ---------------------------------- |
| `pwd`              | Show current working directory     |
| `ls`               | List files and folders             |
| `ls -l`            | Detailed file listing              |
| `cd`               | Change directory                   |
| `mkdir`            | Create a new directory             |
| `touch`            | Create a new empty file            |
| `cp`               | Copy files or directories          |
| `mv`               | Move or rename files               |
| `rm`               | Remove files or directories        |
| `whoami`           | Show current logged-in user        |
| `id`               | Show user ID and group details     |
| `chmod`            | Change file permissions            |
| `chown`            | Change file ownership              |
| `ps -ef`           | Show all running processes         |
| `top`              | Monitor live system processes      |
| `free -m`          | Check memory usage in MB           |
| `df -h`            | Check disk space usage             |
| `uptime`           | Show server uptime and load        |
| `ping`             | Check network connectivity         |
| `curl`             | Test APIs or websites              |
| `ss -tulnp`        | Check listening ports and services |
| `systemctl status` | Check service status               |
******************************************************************************************************
Important Permission Numbers :

| Permission | Meaning                                  |
| ---------- | ---------------------------------------- |
| `777`      | Full access to everyone                  |
| `755`      | Owner full access, others read & execute |
| `644`      | Owner read/write, others read only       |
| `600`      | Owner read/write only                    |

Useful DevOps & SRE Commands :
| Command                     | Purpose                    |
| --------------------------- | -------------------------- |
| `journalctl -xe`            | Check detailed logs        |
| `tail -f /var/log/messages` | Monitor logs live          |
| `netstat -tulnp`            | Check ports                |
| `find / -name file.txt`     | Search file in server      |
| `grep "ERROR" app.log`      | Search text inside file    |
| `du -sh *`                  | Check folder sizes         |
| `history`                   | Show command history       |
| `hostname`                  | Show server hostname       |
| `uname -a`                  | Show OS and kernel details |
| `ip a`                      | Show IP address details    |

Service Management Commands :
| Command                   | Purpose                 |
| ------------------------- | ----------------------- |
| `systemctl start nginx`   | Start service           |
| `systemctl stop nginx`    | Stop service            |
| `systemctl restart nginx` | Restart service         |
| `systemctl enable nginx`  | Enable service on boot  |
| `systemctl disable nginx` | Disable service on boot |
| `systemctl status nginx`  | Check service status    |

File Permission Symbols:
| Symbol | Meaning       |
| ------ | ------------- |
| `r`    | Read          |
| `w`    | Write         |
| `x`    | Execute       |
| `-`    | No permission |


