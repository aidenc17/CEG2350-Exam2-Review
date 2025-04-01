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

**Q7: What is the command to establish an SSH connection to a server?**  
a) ssh 192.168.0.0@ubuntu 
b) ssh ubuntu@192.168.0.0
c) ssh-server  
d) connect ssh ubuntu@192.168.0.0

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

**Q12: What command is used to remove a directory in Linux?**  
a) rm  
b) del  
c) rmdir  
d) delete  

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

**Q18: What bash command is used to check if a file exists?**  
a) test -e file  
b) check file  
c) file exists  
d) if file -exists  

**Q19: Which of the following is used to read user input in a bash script?**  
a) read  
b) get  
c) input  
d) prompt  

**Q21: Which loop in bash will execute a block of code until a condition is met?**  
a) for loop  
b) while loop  
c) until loop  
d) repeat loop  

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
