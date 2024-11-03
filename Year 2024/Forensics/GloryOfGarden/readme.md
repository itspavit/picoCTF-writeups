# PicoCTF Challenge Writeup

**Challenge URL**: [Glory of the Garden - PicoCTF](https://play.picoctf.org/practice/challenge/44?category=4&page=1)

**Challenge Name**: Glory of the Garden

**Category**: Forensics

## Description
In this challenge, we were given an image file named `garden.jpg`. The goal was to find a hidden flag within the file. 

## Solution

### Step 1: Analyze the File with `xxd`
To inspect the raw data of the image, I used the `xxd` command. This tool displays a file in a hexadecimal and ASCII view, making it easier to spot any hidden text or unusual data embedded within the file.

```bash
xxd garden.jpg
```

### Flag will be revealed at the bottom of the output