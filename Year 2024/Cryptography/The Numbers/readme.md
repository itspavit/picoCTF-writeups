# PicoCTF Challenge Writeup

**Challenge Name**: The Numbers  
**Category**: Cryptography  
**Challenge URL**: [The Numbers - PicoCTF](https://play.picoctf.org/practice/challenge/68?category=2&difficulty=1&page=1)  

## Description
The challenge provides us with an image containing a sequence of numbers. The goal is to decode these numbers to reveal a hidden message or flag.

## Solution

### Step 1: Analyze the Sequence
The image contains the following sequence of numbers: 16 9 3 15 3 20 6 { 20 8 5 14 21 13 2 5 18 19 13 1 19 15 14 }

### Step 2: Try different base ciphers. (!6, 26, 32)
None of these worked

### Step 3: Figured the following cipher
Letter Number Code (A1Z26) A=1, B=2, C=3 and so on.

you will find the flag using this [dcode]https://www.dcode.fr/letter-number-cipher


