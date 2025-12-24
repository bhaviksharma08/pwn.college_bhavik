# Linux Luminarium

## Module 2: Pondering Paths

### Challenge 5: Implicit relative paths, from /
**Objective: Understanding the concept of relative path and executing a program from its relative path**

**Commands + Output:**
```bash
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{sNcUffw3JmmYjl5tpyk-YkoCL2t.QX5QTN0wCMwAzNzEzW}
```

**Learnings:**
- Relative path is when the root (denoted by / in linux) is not provided as the starting directory in the path of the file (e.g. challenge/run)

**Flag:**
pwn.college{sNcUffw3JmmYjl5tpyk-YkoCL2t.QX5QTN0wCMwAzNzEzW}