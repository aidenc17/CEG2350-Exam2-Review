# Multiple Choice Quiz on Shells, SSH, Files, Scripting, and Git

---

## 1. Shells:

**Q1: Which of the following is a shell used in Linux?**  
a) PowerShell  
b) bash  
c) cmd  
d) Z shell  

**Q2: Which shell is commonly used in Windows for command-line operations?**  
a) zsh  
b) bash  
c) PowerShell  
d) sh  

---

## 2. SSH (Secure Shell):

**Q6: What is the primary use of SSH?**  
a) To browse the internet securely  
b) To establish a secure, encrypted connection to remote systems  
c) To copy files between systems  
d) To back up system files  


**Q8: Which of the following is a requirement for SSH authentication?**  
a) Password encryption  
b) Public and private key pairs  
c) Username and domain name 
d) Static IP address


---

## 3. Files, Directories, and OS Structure:

**Q10: What command is used to list files and directories in Linux?**  
a) ls  
b) dir  
c) list  
d) show  

**Q11: What command creates a new directory in Linux?**  
a) mkdir  
b) mkdir -new  
c) touch  
d) newdir  


**Q13: What command is used to remove a file in Linux?**  
a) rm  
b) erase  
c) del  
d) remove  

**Q14: Which command in Linux is used to copy files?**  
a) mv  
b) cp  
c) cat  
d) ln  

---

## 4. Scripting:

**Q17: What does the `echo` command do in bash scripting?**  
a) Prints a message to the console  
b) Executes a command  
c) Reads a file  
d) Creates a new file  


---

## 5. Git (Version Control):

**Q23: What does the `git commit -m "message"` command do?**  
a) Stages changes for commit  
b) Commits staged changes with a descriptive message  
c) Pushes committed changes to a remote repository  
d) Creates a new branch 

**Q24: What command is used to check the status of a Git repository?**  
a) git status  
b) git check  
c) git info  
d) git logs  

**Q25: What does the `git pull` command do?**  
a) Downloads and merges changes from a remote repository  
b) Creates a new commit  
c) Uploads local changes to the remote repository  
d) Clones a remote repository  

**Q26: Which command would you use to stage files for commit in Git?**  
a) git push  
b) git stage  
c) git add  
d) git merge  

**Q27: What does the `git clone` command do?**  
a) Creates a new branch  
b) Downloads a remote repository
c) Commits changes to the repository  
d) Adds files to the repository  

---

## 6. Additional Questions:

**Q28: What is the default file extension for bash scripts?**  
a) .txt  
b) .sh  
c) .bash  
d) .bashscript  

**Q29: What does the `chmod` command do in Linux?**  
a) Changes the ownership of a file  
b) Changes the permissions of a file  
c) Moves a file to a new directory  
d) Renames a file  

**Q30: How can you make a bash script executable?**  
a) chmod +x script.sh  
b) bash script.sh  
c) make script.sh executable  
d) execute script.sh  

**Q31: What does the `cat` command do in Linux?**  
a) Creates a new file  
b) Displays the content of a file  
c) Copies a file  
d) Deletes a file  

---


## Questions on `grep`, `sed` and `awk` are here to get you comfortable before the exam.
**Feel free to use past notes or `man` pages on your terminal!!**

**Use the `employees.csv` file located in this repo for the next questions.**


### `grep` Questions:
1. Find all employees in the "Engineering" department.
2. Display lines containing "HR" employees.
3. Find employees whose name contains "John".
4. Show lines with a salary greater than 70000 (you may need to refine this after `grep` using `awk`).
5. Search for employees who joined in the year 2019.

### `sed` Questions:
6. Replace "HR" with "Human Resources" in the dataset.
7. Remove the "Marketing" department from the dataset.
8. Add a "USD" suffix to all salary values.
9. Swap the "Name" and "Department" columns (assume a simple text transformation).
10. Remove the header row from the file.

### `awk` Questions:
11. Print only the names of the employees.
12. Show the name and salary of employees from the "Engineering" department.
13. Calculate and print the average salary of all employees.
14. Find the highest salary in the dataset.
15. Print the names of employees who joined after 2020.

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


