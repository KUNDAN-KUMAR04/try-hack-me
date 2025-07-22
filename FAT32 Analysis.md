TryHackMe FAT32 Analysis Room 

Task 1: Introduction

Question: Are you ready to start analyzing FAT32?

Answer: No Answer Required

Task 2: Environment and Setup

Question: Boot up the VM and continue with the next task.

Answer: No Answer Needed

Task 3: FAT32: Relevancy in Cyber Security

Question 1: What is the name of the attack that targeted the Iranian 
nuclear program?

Answer: Stuxnet

Question 2: What category of tactic is MITRE ATT&CK TA0005?

Answer: Defense Evasion

Task 4: FAT32 Structure: Reserved and FAT Areas

Question 1: We have a hypothetical file B and its cluster chain starts at cluster F and ends at cluster 10. What would be the value of the FAT entry at cluster F?

Answer: 10000000

Question 2: At which offset does the FAT2 table start?

Answer: 00387E00

Task 5: FAT32 Structure: Data Area

Question 1: What is the filename of the file that starts at cluster 9?

Answer: careers.txt

Question 2: What is the creation time of the file that starts at cluster 9?

Answer: F484

Task 6: FAT32: Analysis Techniques and Tools

Question: Which analysis technique can we use to look for hidden files and directories?

Answer: Directory Structure and File Name Analysis

Task 7: T1564.001 Hidden Files and Directories

Question 1: What is the short file name of the hidden file in the M@lL0v3 directory?

Answer: BEMYVA~1

Question 2: What is the flag found during automated analysis?

Answer: THM{F0uNdTh3H!Dd3nF1l3}

Task 8: T1070.006 Indicator Removal: Timestomp

Question 1: What is the Accessed timestamp of the discovered suspicious file?

Answer: 2018-01-10 00:00:00

Question 2: What is the flag found during the automated analysis?

Answer: THM{T1m3St0Mp3D}

Task 9: T1070.004 File Deletion and T1070.009 Clear Persistence

Question 1: Which hexadecimal sequence identifies a deleted file?

Answer: E5

Question 2: What is the output of the deleted PowerShell script after executing it?

Answer: THM{r3Tr!3v3D_3v!d3nC3}

Task 10: Challenge

Question 1: At which offset does the FAT1 table begin?

Answer: 0020FC00

Question 2: What is the name of the hidden directory on the image?

Answer: Exfiltrated_data

Question 3: What is the flag found in the hidden directory?


Answer: THM{D@t@3xf!lL}

Question 4: What is the size (bytes) of the archive file in the hidden directory?

Answer: 10862

Question 5: What is the name of the deleted file that is present on the image?

Answer: Reverseshell.py

Question 6: What is the flag included in the deleted file?

Answer: THM{B@ckD00rF0unD}

Question 7: What is the name of the file that has suspicious timestamp(s)?

Answer: Legal_Affairs_Notes.txt

Question 8: What is the flag included in the file with suspicious timestamps?

Answer: THM{D@t@g@tH3r!nG}

Task 11: Conclusion

Question: Are you ready for the next filesystem?

Answer: No Answer Needed

This room focuses on forensic analysis of FAT32 file systems, covering topics like hidden files, 
timestomping, file deletion recovery, and various MITRE ATT&CK techniques. The walkthrough demonstrates using tools like HxD hex editor and Autopsy for digital forensics analysis.