# Linux Luminarium

## Module 2: Pondering Paths

### Challenge 8: Home sweet home
**Objective: Promoting critical thinking and a deep understanding of the concepts and commands learned till now**

**Commands + Output:**
```bash
hacker@paths~home-sweet-home:~$ touch a
hacker@paths~home-sweet-home:~$ /challenge/run ~/a
Writing the file to /home/hacker/a!
... and reading it back to you:
pwn.college{oGngmHF-7PEQx83WgIIjwahibjt.QXzMDO0wCMwAzNzEzW}
```

**My Approach explained:**
- There is a constraint on the absolute file path, being restricted to 3 characters, out of which, 2 characters have to be dedicated to '~/' for it to be absolute. So, the remaining one character should be the name of the file. I created a file called 'a' and provided '~/a' as argument.

**Flag:**
pwn.college{oGngmHF-7PEQx83WgIIjwahibjt.QXzMDO0wCMwAzNzEzW}