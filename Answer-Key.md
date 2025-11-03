# Answer Key

## Multiple Choice Answers

1. **Q1:**  
   - b) bash

2. **Q2:**  
   - c) PowerShell

3. **Q3:**  
   - b) bash

4. **Q4:**  
   - a) To establish a secure, encrypted connection to remote systems

5. **Q5:**  
   - b) Public and private key pairs

6. **Q6:**  
   - a) Private key

7. **Q7:**  
   - d) 22

8. **Q8:**  
   - a) ls

9. **Q9:**  
   - b) mkdir

10. **Q10:**  
    - a) rm

11. **Q11:**  
    - b) cp

12. **Q12:**  
    - a) Prints the working directory

13. **Q13:**  
    - b) mv

14. **Q14:**  
    - a) Bash

15. **Q15:**  
    - a) `name="John"`

16. **Q16:**  
    - b) `#!/bin/bash`

17. **Q17:**  
    - ```bash
      if [ "$var" -eq 1 ]
      then
          echo "True"
      else
          echo "False"
      fi
      ```

18. **Q18:**  
    - b) `==`

19. **Q19:**  
    - b) `-gt`

20. **Q20:**  
    - ```bash
      for i in {1..5}; do
          echo $i
      done
      ```

21. **Q21:**  
    - a) Repeats commands as long as a condition is true

22. **Q22:**  
    - `[ -e filename ]`

23. **Q23:**  
    - `echo "Hello" >> file.txt`

24. **Q24:**  
    - `-d`

25. **Q25:**  
    - `read`

26. **Q26:**  
    - `read username`

27. **Q27:**  
    - Parses command-line options and arguments

28. **Q28:**  
    - Commits staged changes with a descriptive message

29. **Q29:**  
    - `git status`

30. **Q30:**  
    - Downloads and merges changes from a remote repository

31. **Q31:**  
    - `git add`

32. **Q32:**  
    - Downloads a remote repository

33. **Q33:**  
    - `git log`

34. **Q34:**  
    - `git restore`

35. **Q35:**  
    - `.sh`

36. **Q36:**  
    - Changes the permissions of a file

37. **Q37:**  
    - `chmod +x script.sh`

38. **Q38:**  
    - Displays the content of a file

39. **Q39:**  
    - Changes file ownership

40. **Q40:**  
    - Read and execute

41. **Q41:**  
    - Lists files in a long format with details

42. **Q42:**  
    - Grants execute permission to everyone, but write permission only to the owner

43. **Q43:**  
    - Searches for the word "error" in logfile.txt

44. **Q44:**  
    - Displays disk space usage in human-readable format

45. **Q45:**  
    - Replaces all occurrences of "cat" with "dog" in animals.txt

46. **Q46:**  
    - Overwrites greetings.txt with “Hello World”

47. **Q47:**  
    - Displays the first 5 lines of myfile.txt

48. **Q48:**  
    - Continuously monitors and displays new lines added to a file

49. **Q49:**  
    - Disk usage summary of /home/user in human-readable format


## Practical Exercise Answers (for employees.csv)

### `grep` Answers

50. **Q50:**  
    - `grep "Engineering" employees.csv`

51. **Q51:**  
    - `grep "HR" employees.csv`

52. **Q52:**  
    - `grep -i "john" employees.csv`

53. **Q53:**  
    - `grep -E "[7-9][0-9]{4}" employees.csv | awk '$4 > 70000'`

54. **Q54:**  
    - `grep -E "2019-[0-9]{2}-[0-9]{2}" employees.csv`

55. **Q55:**  
    - `-v` flag inverts matches


### `sed` Answers

56. **Q56:**  
    - `sed -i 's/HR/Human Resources/g' employees.csv`

57. **Q57:**  
    - `sed '/Marketing/d' employees.csv`

58. **Q58:**  
    - `sed -E 's/(,[0-9]+)/\1 USD/' employees.csv`

59. **Q59:**  
    - `sed -E 's/(.*),(.*),(.*)/\2,\1,\3/' employees.csv`

60. **Q60:**  
    - `sed -i '1d' employees.csv`

61. **Q61:**  
    - `-i` edits the file in place


### `awk` Answers

62. **Q62:**  
    - `awk -F',' '{print $2}' employees.csv`

63. **Q63:**  
    - `awk -F',' '$3=="Engineering" {print $2, $4}' employees.csv`

64. **Q64:**  
    - `awk -F',' '{total+=$4; count++} END {print total/count}' employees.csv`

65. **Q65:**  
    - `awk -F',' '{if ($4 > max) max=$4} END {print max}' employees.csv`

66. **Q66:**  
    - `awk -F',' '$5 ~ /202[1-9]/ {print $2}' employees.csv`

67. **Q67:**  
    - `-F` sets field separator

68. **Q68:**  
    - `NF` gives number of fields


## Process Management

69. **Q69:**  
    - `ps`

70. **Q70:**  
    - Sends a signal to a process

71. **Q71:**  
    - `kill -9 1234`

72. **Q72:**  
    - A process that has completed but still has an entry in the table

73. **Q73:**  
    - Displays real-time system resource usage

74. **Q74:**  
    - Process state/status


## Hardware and System Information

83. **Q83:**  
    - Random Access Memory

84. **Q84:**  
    - CPU


## Disk and Storage Management

89. **Q89:**  
    - `lsblk`

91. **Q91:**  
    - `sudo fdisk -l /dev/xvda`

93. **Q93:**  
    - NVMe SSD


## Partition Tables (MBR vs GPT)

94. **Q94:**  
    - Defines how disk space is divided

95. **Q95:**  
    - 4

96. **Q96:**  
    - 2 TB

97. **Q97:**  
    - GPT

98. **Q98:**  
    - It stores multiple copies of the partition table

99. **Q99:**  
    - All of the above

100. **Q100:**  
     - `parted -l`

101. **Q101:**  
     - UEFI


## Filesystems

102. **Q102:**  
     - Create a partition table and partition

103. **Q103:**  
     - `sudo mkfs.ext4 /dev/sdb1`

104. **Q104:**  
     - Attaches a filesystem to a directory

105. **Q105:**  
     - No

106. **Q106:**  
     - `/etc/fstab`

107. **Q107:**  
     - NTFS, FAT32, ext4

108. **Q108:**  
     - ext4


## BIOS and UEFI

110. **Q110:**  
     - Basic Input Output System

111. **Q111:**  
     - In the MBR (first sector of the disk)

112. **Q112:**  
     - UEFI

114. **Q114:**  
     - MBR

115. **Q115:**  
     - EFI System Partition (ESP)
