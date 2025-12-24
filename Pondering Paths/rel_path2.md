# Linux Luminarium

## Module 2: Pondering Paths

### Challenge 6: Explicit relative paths, from /
**Objective: Understanding the concept of relative path and executing a program from its relative path**

**Commands + Output:**
```bash
hacker@paths~explicit-relative-paths-from-:~$ pwd
/home/hacker
hacker@paths~explicit-relative-paths-from-:~$ ../../challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~explicit-relative-paths-from-:~$ cd ../../
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{ckDheMKoDdc03go3OjbkoM20WXR.QXwUTN0wCMwAzNzEzW}
```

**Learnings:**
- .. is the notation of the parent directory (previous directory) to the current directory
- . is the notation used to denote the current directory itself

**Flag:**
pwn.college{ckDheMKoDdc03go3OjbkoM20WXR.QXwUTN0wCMwAzNzEzW}