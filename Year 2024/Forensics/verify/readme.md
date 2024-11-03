# PicoCTF Challenge Writeup

**Challenge URL**: [PicoCTF Challenge](https://play.picoctf.org/practice/challenge/450?category=4&page=1)

**Challenge Name**: [Verify]

**Category**: Cryptography

## Description
This challenge involves decrypting a file to reveal the flag. Given a directory of files, I identified the correct file and decrypted it using a custom decryption script provided in the challenge.

## Solution

### Step 1: Identify the Target File
After exploring the directory structure, I discovered that the target file was located at `files/8eee7195`. This file was identified as the one containing the flag based on the provided hints and challenge clues.

### Step 2: Decrypt the File
To retrieve the flag, I used a decryption script provided in the challenge directory (`decrypt.sh`). The script requires the filename as an argument and decrypts it with the correct key and settings. I ran the following command to decrypt the file:

```bash
./decrypt.sh files/8eee7195

```

### This will display the flag in your terminal
