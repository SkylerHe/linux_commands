# Linux Command Summary

## 1. File and Directory Operations

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `ls`             | List files and directories                         |
| `cd`             | Change directory                                   |
| `pwd`            | Print working directory                            |
| `mkdir`          | Create a new directory                             |
| `rmdir`          | Remove an empty directory                          |
| `rm`             | Remove files or directories                        |
| `cp`             | Copy files or directories                          |
| `mv`             | Move or rename files and directories               |
| `touch`          | Create an empty file or update file timestamps     |
| `cat`            | Display file contents                              |
| `more` / `less`  | View file contents one page at a time              |
| `find`           | Search for files and directories                   |
| `locate`         | Find files by name                                 |
| `du`             | Disk usage of files and directories                |
| `df`             | Report disk space usage                            |

## 2. File Permissions and Ownership

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `chmod`          | Change file permissions                            |
| `chown`          | Change file owner and group                        |
| `chgrp`          | Change group ownership of a file                   |
| `umask`          | Set default file permissions                       |

## 3. Process Management

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `ps`             | Display currently running processes                |
| `top` / `htop`   | Monitor system processes in real-time              |
| `kill`           | Terminate a process by PID                         |
| `killall`        | Terminate processes by name                        |
| `bg`             | Resume a job in the background                     |
| `fg`             | Bring a job to the foreground                      |
| `jobs`           | List jobs running in the background                |
| `nohup`          | Run a command immune to hangups                    |

## 4. Networking

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `ifconfig` / `ip`| Show network interfaces and IP addresses           |
| `ping`           | Test connectivity to a network host                |
| `netstat`        | Display network connections and statistics         |
| `ss`             | Show active connections (similar to `netstat`)     |
| `scp`            | Secure copy files between hosts                    |
| `rsync`          | Sync files between locations (local or remote)     |
| `curl`           | Transfer data from or to a server                  |
| `wget`           | Download files from the web                        |

## 5. User and Group Management

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `useradd`        | Add a new user                                     |
| `userdel`        | Delete a user                                      |
| `usermod`        | Modify a user account                              |
| `groupadd`       | Add a new group                                    |
| `passwd`         | Change a user's password                           |
| `whoami`         | Display the current user                           |
| `su`             | Switch to another user                             |
| `sudo`           | Run commands with superuser privileges             |
| `w`              | Show who is logged on and what they are doing      |

## 6. File Compression and Archiving

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `tar`            | Archive files and directories                      |
| `gzip` / `gunzip`| Compress/decompress files using gzip               |
| `zip` / `unzip`  | Compress/decompress files using zip                |
| `bzip2` / `bunzip2` | Compress/decompress files using bzip2            |

## 7. Disk and Filesystem Management

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `mount`          | Mount a filesystem                                 |
| `umount`         | Unmount a filesystem                               |
| `fsck`           | Check and repair a filesystem                      |
| `mkfs`           | Create a new filesystem                            |
| `fdisk` / `parted` | Partition a hard drive                           |

## 8. Package Management (Debian-based)

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `apt-get`        | Install, upgrade, or remove packages               |
| `apt-cache`      | Search for packages                                |
| `dpkg`           | Debian package manager                             |

## 9. System Monitoring and Info

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `uname -a`       | Display system information                         |
| `uptime`         | Show system uptime and load average                |
| `dmesg`          | Print system boot messages                         |
| `free`           | Display memory usage                               |
| `vmstat`         | Report virtual memory statistics                   |
| `iostat`         | CPU and I/O statistics                             |
| `df`             | Report filesystem disk space usage                 |
| `du`             | Estimate file space usage                          |

## 10. System Shutdown and Reboot

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `shutdown`       | Shutdown or reboot the system                      |
| `reboot`         | Reboot the system                                  |
| `halt`           | Halt the system                                    |
| `poweroff`       | Power off the system                               |

## 11. Text Processing

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `cat`            | Concatenate and display files                      |
| `grep`           | Search text using patterns                         |
| `sed`            | Stream editor for filtering and transforming text  |
| `awk`            | Pattern scanning and text processing               |
| `sort`           | Sort lines of text files                           |
| `uniq`           | Report or filter out repeated lines in a file      |
| `wc`             | Word, line, character, and byte count              |
| `cut`            | Remove sections from each line of files            |
| `diff`           | Compare files line by line                         |

## 12. Miscellaneous

| Command          | Description                                        |
|------------------|----------------------------------------------------|
| `alias`          | Create an alias for a command                      |
| `history`        | Show command history                               |
| `clear`          | Clear the terminal screen                          |
| `man`            | Display the manual page for a command              |
| `echo`           | Display a line of text                             |
| `date`           | Display or set the system date and time            |
| `cal`            | Display a calendar                                 |
| `uptime`         | Show how long the system has been running          |

