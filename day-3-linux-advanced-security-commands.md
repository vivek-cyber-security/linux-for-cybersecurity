## Day 3 – Advanced Linux Commands for Cybersecurity Practice

## Command 1: chmod
- Used to change file permissions
- Important for securing files
- Example:
  chmod 600 secret.txt

## Command 2: chown
- Changes file owner
- Used in access control
- Example:
  sudo chown vivek secret.txt

## Command 3: groups
- Shows groups of current user
- Helps in permission checking
- Example:
  groups

## Command 4: id
- Shows user ID and group ID
- Important in security auditing
- Example:
  id

## Command 5: find
- Used to search files in system
- Very powerful command
- Example:
  find /home -name "*.txt"

## Command 6: grep
- Searches text inside files
- Used in log analysis
- Example:
  grep "error" logfile.txt

## Command 7: grep -i
- Case insensitive search
- Example:
  grep -i "failed" logfile.txt

## Command 8: head
- Shows first 10 lines of file
- Example:
  head logfile.txt

## Command 9: tail
- Shows last 10 lines of file
- Useful for log monitoring
- Example:
  tail logfile.txt

## Command 10: tail -f
- Monitors file live
- Used for real-time log tracking
- Example:
  tail -f /var/log/syslog

## Command 11: wc
- Counts lines, words and characters
- Example:
  wc logfile.txt

## Command 12: sort
- Sorts file content
- Example:
  sort names.txt

## Command 13: uniq
- Removes duplicate lines
- Used with sort
- Example:
  sort names.txt | uniq

## Command 14: cut
- Extracts specific columns
- Example:
  cut -d ":" -f 1 /etc/passwd

## Command 15: awk
- Powerful text processing tool
- Used in log analysis
- Example:
  awk '{print $1}' logfile.txt

## Command 16: ss
- Shows network connections
- Modern replacement of netstat
- Example:
  ss -tuln

## Command 17: ping
- Tests network connectivity
- Example:
  ping google.com

## Command 18: traceroute
- Shows path of network packets
- Example:
  traceroute google.com

## Command 19: hostname
- Displays system hostname
- Example:
  hostname

## Command 20: uptime
- Shows how long system is running
- Example:
  uptime

## Command 21: crontab -l
- Shows scheduled tasks
- Important in malware detection
- Example:
  crontab -l

## Command 22: env
- Displays environment variables
- Example:
  env

## Command 23: which
- Shows path of command
- Example:
  which python

## Command 24: file
- Shows file type
- Useful in malware analysis
- Example:
  file suspicious_file

## Command 25: sha256sum
- Generates file hash
- Used for integrity checking
- Example:
  sha256sum test.txt

## What I Learned
- Linux has powerful security commands
- Log analysis is very important
- File permissions protect sensitive data
- Hashing ensures file integrity
- These commands are used in real cybersecurity jobs

## End of Day 3 Advanced Practice
