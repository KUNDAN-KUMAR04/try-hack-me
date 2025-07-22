TryHackMe NTFS Analysis Room - Complete Answers
Task 1: Introduction
Question: Continue to the next task.
Answer: No answer needed
Task 2: Lab Connection
Question: I have successfully turned on the VM.
Answer: No answer needed
Task 3: NTFS Overview
Question: Which feature does NTFS use to keep track of the changes within the file system?
Answer: journaling
Task 4: NTFS Components
Question: Double-click on the $UsnJrnl file in the $Extend folder; what is the first evidence file you find?
Answer: $J
Task 5: MFT Record Analysis
Question 5.1: Which column indicates that the file is no longer present on the disk?
Answer: In Use
Question 5.2: Examine the MFT record; what is the network sniffer installed on this system in the \Program Files\ directory?
Answer: wireshark
Question 5.3: An anti-forensics tool responsible for wiping out an attacker's traces was installed in the \Downloads\Tools folder. What is the name of the tool?
Answer: DiskWipe.exe
Question 5.4: According to the MFT record, is the anti-forensics tool currently present on the disk? (yay or nay)
Answer: nay
Question 5.5: Examining the MFT record, it seems there is a record of a flag.txt file. What is the parent path of the file?
Answer: .\tmp\secret_directory
Question 5.6: What is the content of the flag.txt file?
Answer: WelDone_You_F0und_M3
Question 5.7: What is the file name associated with the MFT entry number "584574"?
Answer: SharpHound.ps1
Task 6: NTFS Journaling
Question 6.1: What is the text file name associated with entry number 95071 before renaming it?
Answer: New Text Document.txt
Question 6.2: According to the record, what is the first operation performed on the file in the question above?
Answer: FileCreate
Question 6.3: According to the record in $J, what is the count of the rename operation found against secret_code.txt?
Answer: 2
Question 6.4: According to the record, when was the secret_code.txt file deleted?
Answer: 2025-01-15 08:10:04
Task 7: Index Allocation Attribute ($I30) Overview
Question 7.1: How many deleted files or folders are present in the $I30 attribute file that was extracted in this task?
Answer: 52
Question 7.2: What is the parent MFT entry of the nmap directory?
Answer: 512386
Task 8: Conclusion
Question: Continue to complete the room.
Answer: No answer needed
This room focuses on understanding the NTFS file system structure, analyzing the Master File Table (MFT), working with NTFS journaling features like LogFile and $UsnJrnl, and examining index allocation attributes (
I30) for forensic investigations. The exercises use tools like FTK Imager, MFTECmd.exe, and Timeline Explorer to extract and analyze forensic artifacts from NTFS volumes.