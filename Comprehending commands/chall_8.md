# Linux Luminarium

## Module 3: Comprehending Commands

### Challenge 8: removing files

**Commands + Output:**
```bash
hacker@commands~removing-files:~$ rm del*
hacker@commands~removing-files:~$ /ch*/ch*
Excellent removal. Here is your reward:
pwn.college{Up9Pdt-Brpp-lvG9Kn9RR4GWcIA.QX2kDM1wCMwAzNzEzW}
```

**Explanation:**
- Was too lazy to write complete file names, so used * to substitute. For e.g. del* substitutes for delete_me file and /ch*/ch* substitute for /challenge/check
- Linux automatically detects and substitutes the full file names in the command, if file name is found to start with the string given before the *

**Flag:**
pwn.college{Up9Pdt-Brpp-lvG9Kn9RR4GWcIA.QX2kDM1wCMwAzNzEzW}
