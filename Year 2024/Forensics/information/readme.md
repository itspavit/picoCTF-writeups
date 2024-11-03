# PicoCTF Challenge Writeup

**Challenge URL**: [Information - PicoCTF](https://play.picoctf.org/practice/challenge/186?category=4&page=1)

**Challenge Name**: Information

**Category**: Forensics

## Description
In this challenge, we are given a JPEG image file (`cat.jpg`) and are asked to find hidden information, specifically a flag, within the file. The challenge hints that files can contain hidden data within their metadata.

## Solution

### Step 1: Download and Inspect Metadata
First, I downloaded the file `cat.jpg` and used `exiftool` to inspect its metadata. 

```bash
exiftool cat.jpg
```

### Step 2: The license number of the image looked suspicious and figured the base encoding was base64

### Decode the string from base64 to ASCII which will reveal flag
