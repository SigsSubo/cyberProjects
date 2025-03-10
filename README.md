# Google Cybersecurity Certificate Labs & Projects

This repository serves as a personal tracker for labs and projects I've found interesting and educational while completing the Google Cybersecurity Certificate.

<details>
<summary>Lab 1: Create Hash Values</summary>

*Details of this project can be found in the repository under the same file name*

### Overview
In this lab, I explored file hashing and comparison by performing the following steps:

1. **File Inspection**  
   - Examined the home directory for two files and displayed their contents.  
   - Observation: Both files have identical contents.  
     ![File Contents](https://github.com/user-attachments/assets/a9e0b367-ffa5-4fa7-93c3-01bfa492fe28)

2. **Hash Generation**  
   - Used the `sha256sum` hashing algorithm to generate hashes for each file.  
   - Stored the results in `file1hash.txt` and `file2hash.txt`.  
   - Observation: Despite identical file contents, the hash outputs are completely different.  
     ![Hash Output](https://github.com/user-attachments/assets/891041a2-5e6d-4a21-9578-059bc0cd73ed)

3. **Hash Comparison**  
   - Utilized the `cmp` command to compare the hashes byte-by-byte:  
     ```bash
     analyst@df6a534a0ea1:~$ cmp file1hash file2hash 
     file1hash file2hash differ: char 1, line 1

Result: Through this command I notice that the hashes are diffrent at first character in the first line.
</details>
