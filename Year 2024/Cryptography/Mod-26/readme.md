# PicoCTF Challenge Writeup

**Challenge Name**: MOD-26  
**Category**: Cryptography  
**Challenge URL**: [MOD-26 - PicoCTF](https://play.picoctf.org/practice/challenge/418?category=2&difficulty=1&page=1)  
**TOOLS**: [dCode](https://www.dcode.fr/rot-cipher)

## Description
In this challenge, we were provided with a string that appeared to be encoded using a simple cipher. The hint in the challenge title, **MOD-26**, suggested that the solution might involve a modulo 26 operation, which aligns with a ROT cipher, as it shifts characters within the alphabet.

## Solution

### Step 1: Analyze the String
The encoded string provided was: cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_hyLicInt}

### Step 2: Shift the characters by 13 using ROT-13 cipher to reveal flag
