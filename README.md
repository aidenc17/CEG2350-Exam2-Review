# Exam 2 Review

####I highly recomend using your AWS Instance to test all commmands you're not sure of here, and on the actual exams!
---

## 1. Shells:

**Q1: Which of the following is a shell used in Linux?**  
   - [ ] PowerShell
   - [ ] bash
   - [ ] cmd
   - [ ]  Z shell  

**Q2: Which shell is commonly used in Windows for command-line operations?**  
   - [ ] zsh
   - [ ] bash
   - [ ] PowerShell
   - [ ] sh  

---

## 2. SSH (Secure Shell):

**Q6: What is the primary use of SSH?**  
   - [ ] To browse the internet securely
   - [ ] To establish a secure, encrypted connection to remote systems
   - [ ] To copy files between systems
   - [ ] To back up system files     


**Q8: Which of the following is a requirement for SSH authentication?**  
   - [ ] Password encryption
   - [ ] Public and private key pairs
   - [ ] Username and domain name
   - [ ] Static IP address


---

## 3. Files, Directories, and OS Structure:

**Q10: What command is used to list files and directories in Linux?**  
   - [ ] ls
   - [ ] dir
   - [ ] list
   - [ ] show  

**Q11: What command creates a new directory in Linux?**  
   - [ ] mkdir
   - [ ] mkdir -new  
   - [ ] touch
   - [ ] newdir  


**Q13: What command is used to remove a file in Linux?**  
   - [ ] rm
   - [ ] erase
   - [ ] del
   - [ ] remove  

**Q14: Which command in Linux is used to copy files?**  
   - [ ] mv
   - [ ] cp
   - [ ] cat
   - [ ] ln 

---

## 4. Scripting:

# Scripting Basics

2. **Which of the following is a common shell used in Linux scripting?**  
   - [ ] PowerShell  
   - [ ] Bash  
   - [ ] C Shell  
   - [ ] Python  

4. **What is the correct syntax to define a variable in Bash?**  
   - [ ] `var name = "John"`  
   - [ ] `name := "John"`  
   - [ ] `name="John"`  
   - [ ] `let name = "John"`  

# Conditional Statements

7. **What is the correct syntax for an if-else statement in Bash?**  
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

8. **Which operator is used for string comparison in Bash?**  
   - [ ] `==`  
   - [ ] `-eq`  
   - [ ] `===`  
   - [ ] `!=`  

# Loops

10. **What is the correct syntax for a `for` loop in Bash?**  
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

# File Handling
11. **How do you check if a file exists in a Bash script?**  
    - [ ] `[ -e filename ]`  
    - [ ] `if file_exists(filename)`  
    - [ ] `check_file filename`  
    - [ ] `test -f filename`  

12. **Which command appends output to a file instead of overwriting it?**  
    - [ ] `echo "Hello" > file.txt`  
    - [ ] `echo "Hello" >> file.txt`  
    - [ ] `echo "Hello" <<< file.txt`  
    - [ ] `write "Hello" to file.txt`  

# User Input
13. **Which command is used to take user input in a Bash script?**  
    - [ ] `input`  
    - [ ] `read`  
    - [ ] `scan`  
    - [ ] `get`  

14. **How would you store user input into a variable called `username` in Bash?**  
    - [ ] `read username`  
    - [ ] `input username`  
    - [ ] `username = input()`  
    - [ ] `get username`  

 
---

## 5. Git (Version Control):

**Q23: What does the `git commit -m "message"` command do?**  
   - [ ] Stages changes for commit  
   - [ ] Commits staged changes with a descriptive message  
   - [ ] Pushes committed changes to a remote repository  
   - [ ] Creates a new branch 

**Q24: What command is used to check the status of a Git repository?**  
   - [ ] git status  
   - [ ] git check  
   - [ ] git info  
   - [ ] git logs  

**Q25: What does the `git pull` command do?**  
   - [ ] Downloads and merges changes from a remote repository  
   - [ ] Creates a new commit  
   - [ ] Uploads local changes to the remote repository  
   - [ ] Clones a remote repository  

**Q26: Which command would you use to stage files for commit in Git?**  
   - [ ] git push  
   - [ ] git stage  
   - [ ] git add  
   - [ ] git merge  

**Q27: What does the `git clone` command do?**  
   - [ ] Creates a new branch  
   - [ ] Downloads a remote repository
   - [ ] Commits changes to the repository  
   - [ ] Adds files to the repository  

---

## 6. Additional Questions:

**Q28: What is the default file extension for bash scripts?**  
   - [ ] .txt  
   - [ ] .sh  
   - [ ] .bash  
   - [ ] .bashscript  

**Q29: What does the `chmod` command do in Linux?**  
   - [ ] Changes the ownership of a file  
   - [ ] Changes the permissions of a file  
   - [ ] Moves a file to a new directory
   - [ ] Renames a file  

**Q30: How can you make a bash script executable?**  
   - [ ] chmod +x script.sh  
   - [ ] bash script.sh  
   - [ ] make script.sh executable  
   - [ ] execute script.sh  

**Q31: What does the `cat` command do in Linux?**  
   - [ ] Creates a new file  
   - [ ] Displays the content of a file  
   - [ ] Copies a file  
   - [ ] Deletes a file  

---

# Command Functionality

1. **What does the following command do?**  
   ```bash
   ls -l
   ```
   - [ ] Lists all files in the current directory, including hidden ones  
   - [ ] Lists files in a long format with detailed information  
   - [ ] Deletes all files in the current directory  
   - [ ] Creates a new directory  

2. **What does the following command do?**  
   ```bash
   chmod 755 script.sh
   ```
   - [ ] Grants read, write, and execute permissions to all users  
   - [ ] Grants execute permission to everyone, but write permission only to the owner  
   - [ ] Deletes the file `script.sh`  
   - [ ] Copies `script.sh` to another directory  

3. **What does the following command do?**  
   ```bash
   grep "error" logfile.txt
   ```
   - [ ] Replaces all occurrences of "error" with "logfile"  
   - [ ] Searches for the word "error" in `logfile.txt` and displays matching lines  
   - [ ] Deletes lines containing "error" from `logfile.txt`  
   - [ ] Appends "error" to `logfile.txt`  


6. **What does the following command do?**  
   ```bash
   df -h
   ```
   - [ ] Displays disk space usage in human-readable format  
   - [ ] Formats the disk for new installations  
   - [ ] Lists all directories with their size  
   - [ ] Defragments the file system  

7. **What does the following command do?**  
   ```bash
   sed 's/cat/dog/g' animals.txt
   ```
   - [ ] Adds "dog" to every line in `animals.txt`  
   - [ ] Replaces all occurrences of "cat" with "dog" in `animals.txt`  
   - [ ] Deletes lines containing "cat"  
   - [ ] Appends "cat" to the end of each line  

8. **What does the following command do?**  
   ```bash
   echo "Hello World" > greetings.txt
   ```
   - [ ] Appends "Hello World" to `greetings.txt`  
   - [ ] Overwrites `greetings.txt` with "Hello World"  
   - [ ] Prints "Hello World" to the terminal  
   - [ ] Creates a backup of `greetings.txt`  

9. **What does the following command do?**  
   ```bash
   head -n 5 myfile.txt
   ```
   - [ ] Displays the last 5 lines of `myfile.txt`  
   - [ ] Displays the first 5 lines of `myfile.txt`  
   - [ ] Deletes the first 5 lines of `myfile.txt`  
   - [ ] Creates a new file with only the first 5 lines  
## Questions on `grep`, `sed` and `awk` are here to get you comfortable before the exam.
**Feel free to use past notes or `man` pages on your terminal!!**

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


# `grep` Questions

1. **Find all employees in the "Engineering" department.**  
   - [ ] `grep "HR" employees.csv`  
   - [ ] `grep "Engineering" employees.csv`  
   - [ ] `grep -v "Engineering" employees.csv`  
   - [ ] `grep "Engineering" | awk '{print $1}'`  

2. **Display lines containing "HR" employees.**  
   - [ ] `grep "Marketing" employees.csv`  
   - [ ] `grep "HR" employees.csv`  
   - [ ] `grep -i "HR" employees.csv`  
   - [ ] `grep -w "HR" employees.csv`  

3. **Find employees whose name contains "John".**  
   - [ ] `grep "John" employees.csv`  
   - [ ] `grep -i "john" employees.csv`  
   - [ ] `grep "^John" employees.csv`  
   - [ ] `grep "John$" employees.csv`  

4. **Show lines with a salary greater than 70000 (you may need to refine this after `grep` using `awk`).**  
   - [ ] `grep "70000" employees.csv`  
   - [ ] `grep -E "[7-9][0-9]{4}" employees.csv | awk '$4 > 70000'`  
   - [ ] `grep -v "70000" employees.csv`  
   - [ ] `grep "Salary > 70000" employees.csv`  

5. **Search for employees who joined in the year 2019.**  
   - [ ] `grep "2019" employees.csv`  
   - [ ] `grep "^2019" employees.csv`  
   - [ ] `grep -w "2019" employees.csv`  
   - [ ] `grep -E "2019-[0-9]{2}-[0-9]{2}" employees.csv`  

# `sed` Questions

6. **Replace "HR" with "Human Resources" in the dataset.**  
   - [ ] `sed 's/Human Resources/HR/g' employees.csv`  
   - [ ] `sed 's/HR/Human Resources/g' employees.csv`  
   - [ ] `sed -i 's/HR/Human Resources/g' employees.csv`  
   - [ ] `sed 's/HR/Human Resources/' employees.csv`  

7. **Remove the "Marketing" department from the dataset.**  
   - [ ] `sed '/Marketing/d' employees.csv`  
   - [ ] `sed 's/Marketing//g' employees.csv`  
   - [ ] `sed -i 's/Marketing//g' employees.csv`  
   - [ ] `sed '/Marketing/p' employees.csv`  

8. **Add a "USD" suffix to all salary values.**  
   - [ ] `sed 's/$/ USD/' employees.csv`  
   - [ ] `sed -E 's/(,[0-9]+)/\1 USD/' employees.csv`  
   - [ ] `sed 's/$/USD/' employees.csv`  
   - [ ] `sed 's/SALARY/USD/g' employees.csv`  

9. **Swap the "Name" and "Department" columns (assume a simple text transformation).**  
   - [ ] `sed -E 's/(.*),(.*),(.*)/\2,\1,\3/' employees.csv`  
   - [ ] `sed 's/Name,Department/Department,Name/g' employees.csv`  
   - [ ] `sed -E 's/(.*),(.*),(.*)/\3,\1,\2/' employees.csv`  
   - [ ] `sed -i 's/Name,Department/Department,Name/g' employees.csv`  

10. **Remove the header row from the file.**  
   - [ ] `sed -i '1d' employees.csv`  
   - [ ] `sed -i 's/HEADER//' employees.csv`  
   - [ ] `sed -E 's/^Header,//' employees.csv`  
   - [ ] `sed 's/ID,Name,Department,Salary,JoinDate//g' employees.csv`  

# `awk` Questions

11. **Print only the names of the employees.**  
   - [ ] `awk '{print $1}' employees.csv`  
   - [ ] `awk -F',' '{print $2}' employees.csv`  
   - [ ] `awk '{print $2}' employees.csv`  
   - [ ] `awk -F',' '{print $1}' employees.csv`  

12. **Show the name and salary of employees from the "Engineering" department.**  
   - [ ] `awk -F',' '$3=="Engineering" {print $2, $4}' employees.csv`  
   - [ ] `awk -F',' '$2=="Engineering" {print $1, $3}' employees.csv`  
   - [ ] `awk -F',' '$4=="Engineering" {print $2, $3}' employees.csv`  
   - [ ] `awk -F',' '$3=="Engineering" {print $1, $2}' employees.csv`  

13. **Calculate and print the average salary of all employees.**  
   - [ ] `awk -F',' '{total+=$4; count++} END {print total/count}' employees.csv`  
   - [ ] `awk -F',' '{total+=$3; count++} END {print total/count}' employees.csv`  
   - [ ] `awk -F',' '{total+=$4} END {print total/NR}' employees.csv`  
   - [ ] `awk -F',' '{print sum($4)/count}' employees.csv`  

14. **Find the highest salary in the dataset.**  
   - [ ] `awk -F',' 'max<$4 {max=$4} END {print max}' employees.csv`  
   - [ ] `awk -F',' '{if ($4 > max) max=$4} END {print max}' employees.csv`  
   - [ ] `awk -F',' 'max=$4 {if ($4 > max) max=$4} END {print max}' employees.csv`  
   - [ ] `awk -F',' '{print max($4)}' employees.csv`  

15. **Print the names of employees who joined after 2020.**  
   - [ ] `awk -F',' '$5 ~ /202[1-9]/ {print $2}' employees.csv`  
   - [ ] `awk -F',' '$5 > 2020 {print $2}' employees.csv`  
   - [ ] `awk -F',' '$5 ~ /^202[1-9]/ {print $2}' employees.csv`  
   - [ ] `awk -F',' '$5 >= 2020 {print $2}' employees.csv`  
---
# Disk, Partition, and Filesystem Practice Questions

**Keep in mind I have not been to class with you! These are questions to provoke thought and get the wheels turning!**
**If it does not sound like somehting you covered, you probably haven't!!**

These are all based off my notes when I took the course!

# Disk Storage
1. **What is the primary function of a disk?**  
   - [ ] To process data  
   - [ ] To store and retrieve data  
   - [ ] To transmit network signals  
   - [ ] To execute software instructions  

2. **How does an HDD differ from an SSD in terms of operation?**  
   - [ ] HDDs use magnetic platters, while SSDs use flash memory  
   - [ ] HDDs are faster than SSDs  
   - [ ] SSDs require mechanical movement to access data  
   - [ ] SSDs cannot be used as boot drives  

3. **What command would you use to list all block devices on a Linux system?**  
   - [ ] `lsblk`  
   - [ ] `df -h`  
   - [ ] `du -sh`  
   - [ ] `blkid`  

# MBR (Master Boot Record)
4. **What is the purpose of an MBR?**  
   - [ ] To store user files  
   - [ ] To manage RAM allocation  
   - [ ] To hold partition information and bootloader  
   - [ ] To provide file encryption  

5. **Why is MBR not ideal in terms of corruption?**  
   - [ ] It has no redundancy  
   - [ ] It cannot store bootloaders  
   - [ ] It supports too many partitions  
   - [ ] It only works on SSDs  

6. **How many primary partitions can an MBR disk have?**  
   - [ ] 2  
   - [ ] 4  
   - [ ] 6  
   - [ ] 8  

7. **What is the maximum disk size that MBR supports?**  
   - [ ] 1 TB  
   - [ ] 2 TB  
   - [ ] 4 TB  
   - [ ] 8 TB  

# GPT (GUID Partition Table)
8. **What is the maximum storage capacity GPT supports?**  
   - [ ] 2 TB  
   - [ ] 16 TB  
   - [ ] 9.4 ZB  
   - [ ] 128 PB  

9. **How does GPT improve redundancy compared to MBR?**  
   - [ ] It stores multiple copies of the partition table  
   - [ ] It uses more sectors for partitioning  
   - [ ] It has a built-in error correction system  
   - [ ] It does not require a bootloader  

10. **Where is the bootloader stored in a GPT-partitioned system?**  
   - [ ] In the primary partition  
   - [ ] In the EFI System Partition (ESP)  
   - [ ] In the last sector of the disk  
   - [ ] In the master boot record  

11. **How does Windows allow users to view partitions with GPT?**  
   - [ ] Using `diskpart` and Disk Management  
   - [ ] Through the command `lsblk`  
   - [ ] Using BIOS settings  
   - [ ] GPT partitions are not viewable in Windows  

12. **What tool would you use to manage GPT partitions on Linux?**  
   - [ ] `fdisk`  
   - [ ] `gdisk`  
   - [ ] `mkfs`  
   - [ ] `grub-install`  

# MBR vs GPT
13. **Which partitioning scheme is best suited for BIOS-based systems?**  
   - [ ] GPT  
   - [ ] MBR  
   - [ ] LVM  
   - [ ] FAT32  

14. **Why does GPT pair with UEFI better than MBR?**  
   - [ ] It is faster  
   - [ ] It supports more boot options  
   - [ ] It uses less storage  
   - [ ] It encrypts the bootloader  

15. **What is a key advantage of GPT’s redundancy system?**  
   - [ ] It has built-in error correction  
   - [ ] It stores backup partition tables  
   - [ ] It prevents OS corruption  
   - [ ] It allows infinite partitions  

16. **Which partitioning scheme supports partitions larger than 2TB?**  
   - [ ] MBR  
   - [ ] GPT  
   - [ ] FAT32  
   - [ ] NTFS  

17. **What command would you use to check if a disk uses MBR or GPT?**  
   - [ ] `lsblk`  
   - [ ] `parted -l`  
   - [ ] `df -h`  
   - [ ] `du -sh`  

# Partition Management
18. **What tool supports both MBR and GPT partitioning?**  
   - [ ] `fdisk`  
   - [ ] `gdisk`  
   - [ ] `parted`  
   - [ ] `mkfs`  

19. **What is the difference between fdisk, gdisk, and parted?**  
   - [ ] `fdisk` is for MBR, `gdisk` is for GPT, and `parted` supports both  
   - [ ] `fdisk` is a filesystem tool, `gdisk` manages RAM, and `parted` is a bootloader  
   - [ ] They are all equivalent tools  
   - [ ] Only `parted` supports SSDs  

20. **Why does parted apply changes immediately, unlike fdisk and gdisk?**  
   - [ ] It buffers operations before executing  
   - [ ] It modifies disk partitions in real time  
   - [ ] It stores temporary configurations  
   - [ ] It uses a different command syntax  

22. **How can you list all partitions on /dev/xvda?**  
   - [ ] `fdisk -l /dev/xvda`  
   - [ ] `rm -rf /dev/xvda`  
   - [ ] `mkfs -l /dev/xvda`  
   - [ ] `cat /dev/xvda`  

# Storage & Measurement
23. **How does a file system help organize stored data?**  
   - [ ] By arranging files in a structured format  
   - [ ] By compressing all data automatically  
   - [ ] By encrypting all user files  
   - [ ] By limiting storage usage  

# File Systems
24. **What is the root of a filesystem in Windows?**  
   - [ ] `/root`  
   - [ ] `C:\`  
   - [ ] `/home`  
   - [ ] `E:\`  

26. **Name at least three filesystem types.**  
   - [ ] NTFS, FAT32, ext4  
   - [ ] XML, SQL, CSV  
   - [ ] TCP, UDP, IPFS  
   - [ ] BIOS, UEFI, GPT  

27. **What filesystem is standard for macOS?**  
   - [ ] NTFS  
   - [ ] ext4  
   - [ ] APFS  
   - [ ] FAT32  


