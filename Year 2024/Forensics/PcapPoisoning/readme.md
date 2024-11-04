# pcappoisoning - Forensics Challenge (Medium)

**Challenge Name**: pcappoisoning  
**Category**: Forensics  
**Difficulty**: Medium  
**Challenge Link**: [pcappoisoning on PicoCTF](https://play.picoctf.org/practice/challenge/362?category=4&difficulty=2&page=1)  

## Challenge Description
The task involves analyzing a `.pcap` file, presumably from network traffic, to uncover hidden information or a flag. The SOC analyst observed suspicious activity and traced it to this `trace.pcap` file. Your goal is to investigate the file and find the hidden flag.

## Solution Steps

1. **Use strings command to examine**:
   Luckily the first command displayed the flag 
   ```bash
   strings trace.pcap
```