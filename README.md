# CliKodigo
Cheatsheet for basic Windows CLI commands

**cls**: clear command prompt

**help**: provides help info for a specific command

**| more**: pipe long output to view by page

## Basic System Info
**set**: check path where Windows will execute commands

**ver**: check OS version

**systeminfo**: list OS info, system details, processor, memory, etc

## Network Troubleshooting
**ipconfig**: check network information; add /all for more info

**ping [target_name]**: send specific ICMP packet and listen for response

**tracert [target_name]**: traces network route traversed to reach target

**nslookup [target_name]**: looks up host/domain and returns its IP address

**netstat**: displays current network connections and listening ports; add -abon for more options

## File & Disk Management
**cd**: display current drive and directory; add [target_directory] to move into that directory; add .. to go up one level

**dir**: view child directories; add /a for hidden and system files; add /s to include all subdirectories

**tree**: visually represent the child directories and subdirectories

**mkdir [directory_name]**: create a directory

**rmdir [directory_name]**: remove a directory

**type [file_name]**: show contents of text file into screen

**more [file_name]**: show contents of longer text files

**copy [file_name] [file_new_name]**: copy files 

**move [file_name] [target_directory]**: move files

**del [file_name]/erase [file_name]**: delete a file

## Task & Process Management
**tasklist**: list running processes; use /FI to filter

**taskkill /PID [target_pid]**: kill a process

## Other
**chkdsk**: check file system and disk volumes for errors and bad sectors

**driverquery**: list all installed device drivers

**sfc /scannow**: scans system files for corruption and repairs them
