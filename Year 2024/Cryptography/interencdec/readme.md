# PicoCTF Challenge Writeup

**Challenge Name**: interencdec  
**Category**: Cryptography  
**Challenge URL**: [Interencdec - PicoCTF](https://play.picoctf.org/practice/challenge/418?category=2&difficulty=1&page=1)  

## Description
In this challenge, we are provided with a file named `enc_flag` and asked to decode it to retrieve the flag. The challenge hints that we may need to go through multiple decoding steps.

## Solution

### Step 1: Inspect the File
First, I used the `file` command to check the file type and use `cat` to display text
```bash
file enc_flag
```

### Step 2: Decode using base 64
you will get base64 string from cat so decode it and you will get a base64 string again so decode it again (total 2 times)
you will get a flag format string but it is not correct flag so you need to use ROT-13 cipher to get the flag.