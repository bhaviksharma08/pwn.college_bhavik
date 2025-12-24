# Linux Luminarium

## Module 3: Comprehending Commands

### Challenge 1:
**Objective: **

**Commands + Output:**
```bash
hacker@commands~touching-files:~$ touch /tmp/{pwn,college}
hacker@commands~touching-files:~$ /challenge/run
Success! Here is your flag:
pwn.college{Ut6k1Rqv3_FpGLyUq2FM5RYPH93.QXwMDO0wCMwAzNzEzW}
```

**Explanation:**
- touch creates empty files
- I used a list containing two elements, pwn and college, to substitute in the file path, instead of writing 2 arguments separately

**Flag:**
pwn.college{Ut6k1Rqv3_FpGLyUq2FM5RYPH93.QXwMDO0wCMwAzNzEzW}
