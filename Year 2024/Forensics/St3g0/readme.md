# St3go - picoCTF Writeup

**Challenge Name**: St3go  
**Category**: Forensics  
**Platform**: picoCTF  
**Difficulty**: Medium  
**Challenge URL**: [St3go Challenge](https://play.picoctf.org/practice/challenge/68?category=4&difficulty=1&page=1)  

---

## Description
We’re provided with an image file named `pico.flag.png`. The objective is to analyze the image file and uncover hidden data that reveals the flag.

---

## Solution

1. we know that we need to use some kind of steganography tool. 

2. Install zsteg on ur machine using command line sudo gem install zsteg. Make sure you have ruby, ruby-gems installed first.
then run the command zsteg pico.flag.png to reveal hidden info and you will find the flag
