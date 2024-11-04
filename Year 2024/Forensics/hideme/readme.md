# PicoCTF - hideme

**Category:** Forensics  
**Difficulty:** Medium
**Challenge URL:** [PicoCTF hideme](https://play.picoctf.org/practice/challenge/350?category=4&difficulty=2&page=1)  

---

## Challenge Description
> The SOC analyst found a suspicious image file that seemed to have hidden content. They need to investigate it to uncover a hidden message.

---

## Solution

### Step 1: Analyzing the File with `binwalk`
First, we used `binwalk` to check for hidden files or embedded data within the image.

```bash
binwalk -e flag.png
```

This shows that there is a hidden directory named "secret"

### Step 2: Navigate to extracted file

```bash
cd _flag.png.extracted
```

### Step 3: Open the secret directory and open the png file

```bash
cd secret
ls
xdg-open flag.png
```

Once you open the flag.png file you will see the flag