# Exam 2 Review - Complete Study Guide

#### I highly recommend using your AWS Instance to test all commands you're not sure of here, and on the actual exams!

---

## 1. Shells:

**Q1: Which of the following is a shell used in Linux?**  
   - [ ] PowerShell
   - [ ] bash
   - [ ] cmd
   - [ ] Z shell  

**Q2: Which shell is commonly used in Windows for command-line operations?**  
   - [ ] zsh
   - [ ] bash
   - [ ] PowerShell
   - [ ] sh  

**Q3: What is the default shell for most modern Linux distributions?**
   - [ ] sh
   - [ ] csh
   - [ ] bash
   - [ ] fish

---

## 2. SSH (Secure Shell):

**Q4: What is the primary use of SSH?**  
   - [ ] To browse the internet securely
   - [ ] To establish a secure, encrypted connection to remote systems
   - [ ] To copy files between systems
   - [ ] To back up system files     

**Q5: Which of the following is a requirement for SSH authentication?**  
   - [ ] Password encryption
   - [ ] Public and private key pairs
   - [ ] Username and domain name
   - [ ] Static IP address

**Q6: When using SSH key authentication, which key should NEVER be shared?**
   - [ ] Public key
   - [ ] Private key
   - [ ] Host key
   - [ ] Session key

**Q7: What is the default port for SSH connections?**
   - [ ] 21
   - [ ] 22
   - [ ] 80
   - [ ] 443

---

## 3. Files, Directories, and OS Structure:

**Q8: What command is used to list files and directories in Linux?**  
   - [ ] ls
   - [ ] dir
   - [ ] list
   - [ ] show  

**Q9: What command creates a new directory in Linux?**  
   - [ ] mkdir
   - [ ] mkdir -new  
   - [ ] touch
   - [ ] newdir  

**Q10: What command is used to remove a file in Linux?**  
   - [ ] rm
   - [ ] erase
   - [ ] del
   - [ ] remove  

**Q11: Which command in Linux is used to copy files?**  
   - [ ] mv
   - [ ] cp
   - [ ] cat
   - [ ] ln 

**Q12: What does the `pwd` command do?**
   - [ ] Powers down the system
   - [ ] Prints the working directory
   - [ ] Pauses while downloading
   - [ ] Previews word documents

**Q13: Which command would you use to move a file from one location to another?**
   - [ ] cp
   - [ ] mv
   - [ ] transfer
   - [ ] relocate

---

## 4. Scripting:

### Scripting Basics

**Q14: Which of the following is a common shell used in Linux scripting?**  
   - [ ] PowerShell  
   - [ ] Bash  
   - [ ] C Shell  
   - [ ] Python  

**Q15: What is the correct syntax to define a variable in Bash?**  
   - [ ] `var name = "John"`  
   - [ ] `name := "John"`  
   - [ ] `name="John"`  
   - [ ] `let name = "John"`  

**Q16: What line should appear at the beginning of a bash script to specify the interpreter?**
   - [ ] `#/bin/bash`
   - [ ] `#!/bin/bash`
   - [ ] `# bash interpreter`
   - [ ] `<bash>`

### Conditional Statements

**Q17: What is the correct syntax for an if-else statement in Bash?**  
   - [ ]  
     ```bash
     if [ "$var" -eq 1 ]
     then
         echo "True"
     else
         echo "False"
     fi
     ```  
   - [ ]  
     ```bash
     if ($var == 1) {
         echo "True"
     } else {
         echo "False"
     }
     ```  
   - [ ]  
     ```bash
     if var == 1:
         echo "True"
     else:
         echo "False"
     ```  
   - [ ]  
     ```bash
     if "$var" = 1
     {
         echo "True"
     }
     else
     {
         echo "False"
     }
     ```  

**Q18: Which operator is used for string comparison in Bash?**  
   - [ ] `==`  
   - [ ] `-eq`  
   - [ ] `===`  
   - [ ] `!=`  

**Q19: Which test operator checks if a number is greater than another in bash?**
   - [ ] `-gt`
   - [ ] `-ge`
   - [ ] `>`
   - [ ] `-lt`

### Loops

**Q20: What is the correct syntax for a `for` loop in Bash?**  
   - [ ]  
     ```bash
     for i in {1..5}; do
         echo $i
     done
     ```  
   - [ ]  
     ```bash
     for (i = 1; i <= 5; i++) {
         echo $i
     }
     ```  
   - [ ]  
     ```bash
     for i = 1 to 5
         echo $i
     ```  
   - [ ]  
     ```bash
     foreach i (1..5) {
         echo $i
     }
     ```  

**Q21: What does a `while` loop do in bash?**
   - [ ] Executes once then exits
   - [ ] Repeats commands as long as a condition is true
   - [ ] Only works with numeric values
   - [ ] Runs in the background

### File Handling

**Q22: How do you check if a file exists in a Bash script?**  
   - [ ] `[ -e filename ]`  
   - [ ] `if file_exists(filename)`  
   - [ ] `check_file filename`  
   - [ ] `test -f filename`  

**Q23: Which command appends output to a file instead of overwriting it?**  
   - [ ] `echo "Hello" > file.txt`  
   - [ ] `echo "Hello" >> file.txt`  
   - [ ] `echo "Hello" <<< file.txt`  
   - [ ] `write "Hello" to file.txt`  

**Q24: What test flag checks if a path is a directory?**
   - [ ] `-f`
   - [ ] `-d`
   - [ ] `-e`
   - [ ] `-dir`

### User Input

**Q25: Which command is used to take user input in a Bash script?**  
   - [ ] `input`  
   - [ ] `read`  
   - [ ] `scan`  
   - [ ] `get`  

**Q26: How would you store user input into a variable called `username` in Bash?**  
   - [ ] `read username`  
   - [ ] `input username`  
   - [ ] `username = input()`  
   - [ ] `get username`  

**Q27: What does the `getopts` command do in a bash script?**
   - [ ] Gets system options
   - [ ] Parses command-line options and arguments
   - [ ] Optimizes script performance
   - [ ] Gets user preferences

---

## 5. Git (Version Control):

**Q28: What does the `git commit -m "message"` command do?**  
   - [ ] Stages changes for commit  
   - [ ] Commits staged changes with a descriptive message  
   - [ ] Pushes committed changes to a remote repository  
   - [ ] Creates a new branch 

**Q29: What command is used to check the status of a Git repository?**  
   - [ ] git status  
   - [ ] git check  
   - [ ] git info  
   - [ ] git logs  

**Q30: What does the `git pull` command do?**  
   - [ ] Downloads and merges changes from a remote repository  
   - [ ] Creates a new commit  
   - [ ] Uploads local changes to the remote repository  
   - [ ] Clones a remote repository  

**Q31: Which command would you use to stage files for commit in Git?**  
   - [ ] git push  
   - [ ] git stage  
   - [ ] git add  
   - [ ] git merge  

**Q32: What does the `git clone` command do?**  
   - [ ] Creates a new branch  
   - [ ] Downloads a remote repository
   - [ ] Commits changes to the repository  
   - [ ] Adds files to the repository  

**Q33: What command shows the commit history of a repository?**
   - [ ] git history
   - [ ] git log
   - [ ] git commits
   - [ ] git show

**Q34: If you want to undo changes in your working directory, which command should you use?**
   - [ ] git undo
   - [ ] git revert
   - [ ] git restore
   - [ ] git reset

---

## 6. Linux Commands and Permissions:

**Q35: What is the default file extension for bash scripts?**  
   - [ ] .txt  
   - [ ] .sh  
   - [ ] .bash  
   - [ ] .bashscript  

**Q36: What does the `chmod` command do in Linux?**  
   - [ ] Changes the ownership of a file  
   - [ ] Changes the permissions of a file  
   - [ ] Moves a file to a new directory
   - [ ] Renames a file  

**Q37: How can you make a bash script executable?**  
   - [ ] chmod +x script.sh  
   - [ ] bash script.sh  
   - [ ] make script.sh executable  
   - [ ] execute script.sh  

**Q38: What does the `cat` command do in Linux?**  
   - [ ] Creates a new file  
   - [ ] Displays the content of a file  
   - [ ] Copies a file  
   - [ ] Deletes a file  

**Q39: What does the `chown` command do?**
   - [ ] Changes file permissions
   - [ ] Changes file ownership
   - [ ] Changes file location
   - [ ] Changes file name

**Q40: In the permission string `-rwxr-xr--`, what permissions does the group have?**
   - [ ] Read, write, execute
   - [ ] Read and execute
   - [ ] Read only
   - [ ] Execute only

---

## 7. Command Functionality:

**Q41: What does the following command do?**  
   ```bash
   ls -l
   ```
   - [ ] Lists all files in the current directory, including hidden ones  
   - [ ] Lists files in a long format with detailed information  
   - [ ] Deletes all files in the current directory  
   - [ ] Creates a new directory  

**Q42: What does the following command do?**  
   ```bash
   chmod 755 script.sh
   ```
   - [ ] Grants read, write, and execute permissions to all users  
   - [ ] Grants execute permission to everyone, but write permission only to the owner  
   - [ ] Deletes the file `script.sh`  
   - [ ] Copies `script.sh` to another directory  

**Q43: What does the following command do?**  
   ```bash
   grep "error" logfile.txt
   ```
   - [ ] Replaces all occurrences of "error" with "logfile"  
   - [ ] Searches for the word "error" in `logfile.txt` and displays matching lines  
   - [ ] Deletes lines containing "error" from `logfile.txt`  
   - [ ] Appends "error" to `logfile.txt`  

**Q44: What does the following command do?**  
   ```bash
   df -h
   ```
   - [ ] Displays disk space usage in human-readable format  
   - [ ] Formats the disk for new installations  
   - [ ] Lists all directories with their size  
   - [ ] Defragments the file system  

**Q45: What does the following command do?**  
   ```bash
   sed 's/cat/dog/g' animals.txt
   ```
   - [ ] Adds "dog" to every line in `animals.txt`  
   - [ ] Replaces all occurrences of "cat" with "dog" in `animals.txt`  
   - [ ] Deletes lines containing "cat"  
   - [ ] Appends "cat" to the end of each line  

**Q46: What does the following command do?**  
   ```bash
   echo "Hello World" > greetings.txt
   ```
   - [ ] Appends "Hello World" to `greetings.txt`  
   - [ ] Overwrites `greetings.txt` with "Hello World"  
   - [ ] Prints "Hello World" to the terminal  
   - [ ] Creates a backup of `greetings.txt`  

**Q47: What does the following command do?**  
   ```bash
   head -n 5 myfile.txt
   ```
   - [ ] Displays the last 5 lines of `myfile.txt`  
   - [ ] Displays the first 5 lines of `myfile.txt`  
   - [ ] Deletes the first 5 lines of `myfile.txt`  
   - [ ] Creates a new file with only the first 5 lines  

**Q48: What does the command `tail -f logfile.txt` do?**
   - [ ] Shows the last 10 lines and exits
   - [ ] Continuously monitors and displays new lines added to the file
   - [ ] Displays file metadata
   - [ ] Deletes the last few lines

**Q49: What does `du -sh /home/user` display?**
   - [ ] Disk usage summary of /home/user in human-readable format
   - [ ] Available disk space
   - [ ] File count in directory
   - [ ] Disk partitions

---

## 8. Text Processing Practice (grep, sed, awk):

**For the next sections, use the text below.**
**It is in the file `employees.csv`**

```
ID,Name,Department,Salary,JoinDate
101,John Doe,Engineering,85000,2019-06-15
102,Jane Smith,Marketing,62000,2021-03-22
103,Alice Johnson,Engineering,95000,2018-09-10
104,Bob Brown,HR,54000,2020-01-17
105,Charlie Davis,Engineering,72000,2022-07-29
106,Emily Wilson,Marketing,68000,2017-12-05
107,David White,HR,58000,2016-11-03
108,Grace Hall,Engineering,87000,2019-10-30
109,Frank Harris,Marketing,64000,2023-02-12
110,Eva Lewis,HR,60000,2018-04-14
```

### `grep` Questions

**Q50: Find all employees in the "Engineering" department.**  
   - [ ] `grep "HR" employees.csv`  
   - [ ] `grep "Engineering" employees.csv`  
   - [ ] `grep -v "Engineering" employees.csv`  
   - [ ] `grep "Engineering" | awk '{print $1}'`  

**Q51: Display lines containing "HR" employees.**  
   - [ ] `grep "Marketing" employees.csv`  
   - [ ] `grep "HR" employees.csv`  
   - [ ] `grep -i "HR" employees.csv`  
   - [ ] `grep -w "HR" employees.csv`  

**Q52: Find employees whose name contains "John".**  
   - [ ] `grep "John" employees.csv`  
   - [ ] `grep -i "john" employees.csv`  
   - [ ] `grep "^John" employees.csv`  
   - [ ] `grep "John$" employees.csv`  

**Q53: Show lines with a salary greater than 70000 (you may need to refine this after `grep` using `awk`).**  
   - [ ] `grep "70000" employees.csv`  
   - [ ] `grep -E "[7-9][0-9]{4}" employees.csv | awk '$4 > 70000'`  
   - [ ] `grep -v "70000" employees.csv`  
   - [ ] `grep "Salary > 70000" employees.csv`  

**Q54: Search for employees who joined in the year 2019.**  
   - [ ] `grep "2019" employees.csv`  
   - [ ] `grep "^2019" employees.csv`  
   - [ ] `grep -w "2019" employees.csv`  
   - [ ] `grep -E "2019-[0-9]{2}-[0-9]{2}" employees.csv`  

**Q55: What does the `-v` flag do in grep?**
   - [ ] Shows version information
   - [ ] Inverts the match (shows non-matching lines)
   - [ ] Enables verbose mode
   - [ ] Validates the pattern

### `sed` Questions

**Q56: Replace "HR" with "Human Resources" in the dataset.**  
   - [ ] `sed 's/Human Resources/HR/g' employees.csv`  
   - [ ] `sed 's/HR/Human Resources/g' employees.csv`  
   - [ ] `sed -i 's/HR/Human Resources/g' employees.csv`  
   - [ ] `sed 's/HR/Human Resources/' employees.csv`  

**Q57: Remove the "Marketing" department from the dataset.**  
   - [ ] `sed '/Marketing/d' employees.csv`  
   - [ ] `sed 's/Marketing//g' employees.csv`  
   - [ ] `sed -i 's/Marketing//g' employees.csv`  
   - [ ] `sed '/Marketing/p' employees.csv`  

**Q58: Add a "USD" suffix to all salary values.**  
   - [ ] `sed 's/$/ USD/' employees.csv`  
   - [ ] `sed -E 's/(,[0-9]+)/\1 USD/' employees.csv`  
   - [ ] `sed 's/$/USD/' employees.csv`  
   - [ ] `sed 's/SALARY/USD/g' employees.csv`  

**Q59: Swap the "Name" and "Department" columns (assume a simple text transformation).**  
   - [ ] `sed -E 's/(.*),(.*),(.*)/\2,\1,\3/' employees.csv`  
   - [ ] `sed 's/Name,Department/Department,Name/g' employees.csv`  
   - [ ] `sed -E 's/(.*),(.*),(.*)/\3,\1,\2/' employees.csv`  
   - [ ] `sed -i 's/Name,Department/Department,Name/g' employees.csv`  

**Q60: Remove the header row from the file.**  
   - [ ] `sed -i '1d' employees.csv`  
   - [ ] `sed -i 's/HEADER//' employees.csv`  
   - [ ] `sed -E 's/^Header,//' employees.csv`  
   - [ ] `sed 's/ID,Name,Department,Salary,JoinDate//g' employees.csv`  

**Q61: What does the `-i` flag do in sed?**
   - [ ] Ignores case
   - [ ] Edits the file in-place
   - [ ] Shows line numbers
   - [ ] Enables interactive mode

### `awk` Questions

**Q62: Print only the names of the employees.**  
   - [ ] `awk '{print $1}' employees.csv`  
   - [ ] `awk -F',' '{print $2}' employees.csv`  
   - [ ] `awk '{print $2}' employees.csv`  
   - [ ] `awk -F',' '{print $1}' employees.csv`  

**Q63: Show the name and salary of employees from the "Engineering" department.**  
   - [ ] `awk -F',' '$3=="Engineering" {print $2, $4}' employees.csv`  
   - [ ] `awk -F',' '$2=="Engineering" {print $1, $3}' employees.csv`  
   - [ ] `awk -F',' '$4=="Engineering" {print $2, $3}' employees.csv`  
   - [ ] `awk -F',' '$3=="Engineering" {print $1, $2}' employees.csv`  

**Q64: Calculate and print the average salary of all employees.**  
   - [ ] `awk -F',' '{total+=$4; count++} END {print total/count}' employees.csv`  
   - [ ] `awk -F',' '{total+=$3; count++} END {print total/count}' employees.csv`  
   - [ ] `awk -F',' '{total+=$4} END {print total/NR}' employees.csv`  
   - [ ] `awk -F',' '{print sum($4)/count}' employees.csv`  

**Q65: Find the highest salary in the dataset.**  
   - [ ] `awk -F',' 'max<$4 {max=$4} END {print max}' employees.csv`  
   - [ ] `awk -F',' '{if ($4 > max) max=$4} END {print max}' employees.csv`  
   - [ ] `awk -F',' 'max=$4 {if ($4 > max) max=$4} END {print max}' employees.csv`  
   - [ ] `awk -F',' '{print max($4)}' employees.csv`  

**Q66: Print the names of employees who joined after 2020.**  
   - [ ] `awk -F',' '$5 ~ /202[1-9]/ {print $2}' employees.csv`  
   - [ ] `awk -F',' '$5 > 2020 {print $2}' employees.csv`  
   - [ ] `awk -F',' '$5 ~ /^202[1-9]/ {print $2}' employees.csv`  
   - [ ] `awk -F',' '$5 >= 2020 {print $2}' employees.csv`  

**Q67: What does the `-F` flag specify in awk?**
   - [ ] File to process
   - [ ] Field separator
   - [ ] Function to execute
   - [ ] Filter pattern

**Q68: In awk, what does `NF` represent?**
   - [ ] Number of fields in current record
   - [ ] New file indicator
   - [ ] Next field to process
   - [ ] Numeric format

---

## 9. Process Management:

**Q69: What command shows currently running processes?**
   - [ ] `show processes`
   - [ ] `ps`
   - [ ] `list`
   - [ ] `proc`

**Q70: What does the `kill` command do?**
   - [ ] Terminates the system
   - [ ] Sends a signal to a process
   - [ ] Deletes a file
   - [ ] Stops all processes

**Q71: Given a process with PID 1234, write the command to terminate it forcefully.**

**Answer:** ________________________________

**Q72: What does a zombie process indicate?**
   - [ ] A process consuming too much CPU
   - [ ] A process that has completed but still has an entry in the process table
   - [ ] A virus on the system
   - [ ] A sleeping process

**Q73: What does the `top` command do?**
   - [ ] Shows the top files by size
   - [ ] Displays real-time system resource usage and processes
   - [ ] Lists the most recently modified files
   - [ ] Shows disk usage

**Q74: In `ps` output, what does the STAT column show?**
   - [ ] Process statistics
   - [ ] Process state/status
   - [ ] Start time
   - [ ] CPU percentage

---

## 11. Hardware and System Information:

**Q83: What does RAM stand for?**
   - [ ] Read Access Memory
   - [ ] Random Access Memory
   - [ ] Rapid Application Memory
   - [ ] Remote Access Module

**Q84: Which component is responsible for executing program instructions?**
   - [ ] RAM
   - [ ] CPU
   - [ ] GPU
   - [ ] Motherboard

---

## 13. Disk and Storage Management:

**Q89: What command lists block devices?**
   - [ ] `lsblk`
   - [ ] `listdisk`
   - [ ] `showdisk`
   - [ ] `blkinfo`

**Q91: Write a command to view the partition table of `/dev/xvda`.**

**Answer:** ________________________________

**Q93: Which storage technology is typically fastest?**
   - [ ] HDD
   - [ ] SATA SSD
   - [ ] NVMe SSD
   - [ ] USB flash drive

---

## 14. Partition Tables (MBR vs GPT):

**Q94: What is the primary function of a partition table?**
   - [ ] To process data
   - [ ] To define how disk space is divided
   - [ ] To encrypt data
   - [ ] To backup files

**Q95: What is the maximum number of primary partitions in MBR?**
   - [ ] 2
   - [ ] 4
   - [ ] 8
   - [ ] Unlimited

**Q96: What is the maximum disk size that MBR supports?**
   - [ ] 1 TB
   - [ ] 2 TB
   - [ ] 4 TB
   - [ ] 8 TB

**Q97: What partition scheme should be used for disks larger than 2TB?**
   - [ ] MBR
   - [ ] GPT
   - [ ] FAT32
   - [ ] NTFS

**Q98: How does GPT provide redundancy?**
   - [ ] It stores multiple copies of the partition table
   - [ ] It uses RAID
   - [ ] It compresses data
   - [ ] It doesn't provide redundancy

**Q99: Which partitioning tool works with both MBR and GPT?**
   - [ ] `fdisk`
   - [ ] `gdisk`
   - [ ] `parted`
   - [ ] All of the above

**Q100: What command checks if a disk uses MBR or GPT?**
   - [ ] `parted -l`
   - [ ] `disktype`
   - [ ] `lsblk -f`
   - [ ] Both a and c

**Q101: Which boot firmware is typically paired with GPT?**
   - [ ] BIOS
   - [ ] UEFI
   - [ ] MBR
   - [ ] GRUB

---

## 15. Filesystems:

**Q102: What must you do before creating a filesystem on a partition?**
   - [ ] Mount it
   - [ ] Create a partition table and partition
   - [ ] Format the entire disk
   - [ ] Install an OS

**Q103: What command creates an ext4 filesystem on `/dev/sdb1`?**

**Answer:** ________________________________

**Q104: What does the `mount` command do?**
   - [ ] Attaches a filesystem to a directory
   - [ ] Creates a new filesystem
   - [ ] Deletes a partition
   - [ ] Formats a disk

**Q105: When you unmount a filesystem, is the data deleted?**
   - [ ] Yes
   - [ ] No

**Q106: What file contains permanent mount configurations for filesystems to mount at boot?**
   - [ ] `/etc/mounts`
   - [ ] `/etc/fstab`
   - [ ] `/etc/filesystem`
   - [ ] `/boot/mounts.conf`

**Q107: What are three common filesystem types?**
   - [ ] NTFS, FAT32, ext4
   - [ ] TCP, UDP, HTTP
   - [ ] MBR, GPT, LVM
   - [ ] BIOS, UEFI, GRUB

**Q108: What is the standard filesystem for modern Linux?**
   - [ ] ext3
   - [ ] ext4
   - [ ] NTFS
   - [ ] FAT32

---

## 16. BIOS and UEFI:

**Q110: What does BIOS stand for?**
   - [ ] Basic Input Output System
   - [ ] Binary Integrated Operating System
   - [ ] Boot Installation Operating System
   - [ ] Base Input Operating Sequence

**Q111: Where does BIOS store the bootloader?**
   - [ ] In the MBR (first sector of disk)
   - [ ] In an EFI partition
   - [ ] In the root directory
   - [ ] In RAM

**Q112: Which boot firmware supports Secure Boot?**
   - [ ] BIOS
   - [ ] UEFI
   - [ ] Both
   - [ ] Neither

**Q114: What partition scheme does BIOS typically use?**
   - [ ] GPT
   - [ ] MBR
   - [ ] LVM
   - [ ] ext4

**Q115: Where are bootloaders stored in a UEFI system?**
   - [ ] MBR
   - [ ] EFI System Partition (ESP)
   - [ ] Root partition
   - [ ] Boot sector

---

## 17. Linux Boot Process:

**Q116: What is the first process that starts in Linux?**
   - [ ] bash
   - [ ] systemd/init
   - [ ] kernel
   - [ ] grub

**Q117: What loads the Linux kernel into memory?**
   - [ ] BIOS
   - [ ] Bootloader (GRUB)
   - [ ] systemd
   - [ ] init

**Q118: What is the role of initramfs during boot?**
   - [ ] Provides a graphical interface
   - [ ] Provides drivers and tools to mount the root filesystem
   - [ ] Manages user logins
   - [ ] Starts network services

**Q119: In what order do these boot steps occur?**
   - [ ] BIOS/UEFI → Bootloader → Kernel → Init system
   - [ ] Kernel → BIOS → Bootloader → Init system
   - [ ] Bootloader → BIOS → Kernel → Init system
   - [ ] Init system → Kernel → BIOS → Bootloader

---

## 18. Package Management:

**Q121: What does `apt update` do?**
   - [ ] Updates all installed packages
   - [ ] Refreshes the package list from repositories
   - [ ] Updates the kernel
   - [ ] Updates only security packages

**Q123: Write a command to install a package named "nginx" using apt.**

**Answer:** ________________________________

---

## 19. PATH and Command Execution:

**Q127: What is the PATH environment variable?**
   - [ ] The current directory location
   - [ ] A list of directories where the system looks for executables
   - [ ] The path to the home directory
   - [ ] A list of recently used commands

**Q128: How do you view the PATH variable?**
   - [ ] `echo $PATH`
   - [ ] `printenv PATH`
   - [ ] `cat $PATH`
   - [ ] Both a and b

**Q129: What character separates directories in the PATH variable?**
   - [ ] Semicolon (;)
   - [ ] Colon (:)
   - [ ] Comma (,)
   - [ ] Pipe (|)

**Q130: If a command is *not* in your PATH, how can you execute it from the current directory?**
   - [ ] `command_name`
   - [ ] `./command_name`
   - [ ] `run command_name`
   - [ ] `exec command_name`

**Q131: What does the `which` command do?**
   - [ ] Shows which user is logged in
   - [ ] Shows the full path to an executable
   - [ ] Shows which processes are running
   - [ ] Shows which files are open

---

## 20. Aliases and Shortcuts:

**Q133: What is an alias in bash?**
   - [ ] A shortcut name for a command or series of commands
   - [ ] An alternative username
   - [ ] A symbolic link
   - [ ] A variable

**Q134: Write a command to create an alias called "ll" that runs "ls -la".**

**Answer:** ________________________________

**Q135: Where should you save aliases permanently?**
   - [ ] `/etc/profile`
   - [ ] `/etc/aliases`
   - [ ] `~/.bash_aliases`


**Q137: If you have a program called "shivermetimbers" but want to type "timbers" instead, what's a good solution?**
   - [ ] Rename the file
   - [ ] Create an alias
   - [ ] Create a symbolic link
   - [ ] Both b and c

---

## 22. Additional System Commands:

**Q143: What does the `df` command show?**
   - [ ] Disk free space
   - [ ] Directory files
   - [ ] Data format
   - [ ] Disk fragments

**Q146: What does `history | grep ssh` do?**
   - [ ] Shows SSH configuration
   - [ ] Searches command history for lines containing "ssh"
   - [ ] Connects via SSH
   - [ ] Lists SSH keys

**Q147: What does the `man` command do?**
   - [ ] Manages users
   - [ ] Shows manual pages for commands
   - [ ] Manipulates files
   - [ ] Monitors system

---

## 23. File Operations:

**Q149: What is the difference between `>` and `>>` in output redirection?**
   - [ ] No difference
   - [ ] `>` overwrites; `>>` appends
   - [ ] `>` appends; `>>` overwrites
   - [ ] `>` is for errors; `>>` is for output

**Q152: What does the `find` command do?**
   - [ ] Searches for text within files
   - [ ] Searches for files and directories
   - [ ] Finds duplicate files
   - [ ] Recovers deleted files

---

## 25. Permissions and Security:

**Q159: What do the numbers in `chmod 644` represent?**
   - [ ] Owner: rw-, Group: r--, Other: r--
   - [ ] Owner: r--, Group: rw-, Other: rw-
   - [ ] Owner: rwx, Group: r--, Other: r--
   - [ ] Everyone: rw-

**Q160: What does `sudo` do?**
   - [ ] Switches user
   - [ ] Runs a command with superuser privileges
   - [ ] Shuts down the system
   - [ ] Shows user details

**Q161: How do you switch to the root user?**
   - [ ] `sudo su`
   - [ ] `su root`
   - [ ] `su -`
   - [ ] All of the above

**Q162: What permission is needed to execute a script?**
   - [ ] Read
   - [ ] Write
   - [ ] Execute
   - [ ] All of the above

**Q163: What does `chmod u+x file.sh` do?**
   - [ ] Adds execute permission for the user (owner)
   - [ ] Removes execute permission
   - [ ] Adds execute for everyone
   - [ ] Changes the user owner

---

## 26. BONUS Questions:

**Q164: [BONUS] Write a complete command pipeline that lists all `.log` files in `/var/log`, searches for lines containing "ERROR", and counts how many matches are found.**

**Answer:** ________________________________

**Q165: [BONUS] Explain what this command does and why each part is important:**
```bash
sudo find / -name "*.tmp" -type f -mtime +7 -delete
```

**Answer:** ________________________________


**Q167: [BONUS] What is the difference between a hard link and a symbolic link?**

**Answer:** ________________________________

---

## End of Study Guide

**Remember to practice these commands on your AWS instance!**
**Good luck on your exam!**
