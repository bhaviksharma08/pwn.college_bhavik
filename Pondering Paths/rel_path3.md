# Linux Luminarium

## Module 2: Pondering Paths

### Challenge 7: Implicit relative path
**Objective: Executing a program from just its name while avoiding ambiguity with a linux system command**

**Commands:**
```bash
1) cd /challenge
2) ./run
```

**Output:**
```bash
1) hacker@paths~implicit-relative-path:/challenge$
2) Correct!!!
   ./run is a relative path, invoked from the right directory!
   Here is your flag:
   pwn.college{o5iCDseK4gjxXUJLpP-KP1bcRpz.QXxUTN0wCMwAzNzEzW}
```

**Learnings:**
- We can use implicit relative path to execute the program. If we just specify the name of the program in its directory and hit enter, linux will confuse it for a system command. Instead, we can execute the file by specifying its path relative to the current directory '.' as: ./run

**Flag:**
pwn.college{o5iCDseK4gjxXUJLpP-KP1bcRpz.QXxUTN0wCMwAzNzEzW}