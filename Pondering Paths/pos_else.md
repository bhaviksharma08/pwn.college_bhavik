# Linux Luminarium

## Module 2: Pondering Paths

### Challenge 4: Position elsewhere

**Commands + Output:**
```bash
hacker@paths~position-elsewhere:~$ /challenge/run
Starting level 1.
Incorrect...
You are not currently in the /etc/apt/sources.list.d directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-elsewhere:~$ cd /etc/apt/sources.list.d
hacker@paths~position-elsewhere:/etc/apt/sources.list.d$ /challenge/run
Starting level 1.
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 2
Please use the `cd` utility to change directory to /var/lib/apt/lists
hacker@paths~position-elsewhere:/etc/apt/sources.list.d$ cd /var/lib/apt/lists
hacker@paths~position-elsewhere:/var/lib/apt/lists$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 3
Please use the `cd` utility to change directory to /usr/share/zoneinfo/posix/Asia
hacker@paths~position-elsewhere:/var/lib/apt/lists$ cd /usr/share/zoneinfo/posix/Asia
hacker@paths~position-elsewhere:/usr/share/zoneinfo/posix/Asia$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 4
Please use the `cd` utility to change directory to /usr/share/build-essential
hacker@paths~position-elsewhere:/usr/share/zoneinfo/posix/Asia$ cd /usr/share/build-essential
hacker@paths~position-elsewhere:/usr/share/build-essential$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 5
Please use the `cd` utility to change directory to /tmp
hacker@paths~position-elsewhere:/usr/share/build-essential$ cd /tmp
hacker@paths~position-elsewhere:/tmp$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{sY135pR1YGrCF2rBIABXJRAIB37.QX3QTN0wCMwAzNzEzW}
```

**Flag:**
pwn.college{sY135pR1YGrCF2rBIABXJRAIB37.QX3QTN0wCMwAzNzEzW}