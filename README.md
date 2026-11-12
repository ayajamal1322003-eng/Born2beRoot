
# Born2beRoot

## Description
Born2beRoot is a system administration project at 42. The goal is to configure and secure a Linux virtual machine.

## Operating System
- Debian Linux
- VirtualBox
- LVM with encrypted partitions

## Security Configuration
- Password policy using PAM
- Sudo configuration and logging
- SSH configuration
- UFW firewall

## Monitoring
A Bash script named `monitoring.sh` displays system information, including CPU, RAM, disk usage, network information, and active users.

## Technical Choices
- Debian: A stable Linux distribution.
- LVM: Flexible disk and partition management.
- UFW: Simplifies firewall configuration.
- SSH: Provides secure remote access.

## Submission
The `signature.txt` file contains the SHA-1 signature of the virtual disk.
