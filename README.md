# linuxbashscript
Author - Ehtisham Hassan


# Daily File Backup Script (backup.sh)

This Bash script automates the process of backing up files that were modified in the last 24 hours from a specified **source directory** to a **destination directory**.

## What It Does

- Scans a target directory for files modified in the past 24 hours
- Compresses them into a timestamped `.tar.gz` archive
- Moves the archive to the destination directory
- Can be scheduled to run daily using `crontab`

---

##  Usage

```bash
./backup.sh <source_directory> <destination_directory>
--- 

# Example 
./backup.sh /home/user/documents /home/user/backups


