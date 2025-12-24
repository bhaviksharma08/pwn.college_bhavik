# Matching with *
### Challenge Description: To change directory to /challenge without using more than 4 characters of the word 'challenge'
Solving: Using * to substitute 'allenge' and using only 2 characters, 'ch'
Commands:
```
hacker@globbing~matching-with-:~$ cd /ch*
hacker@globbing~matching-with-:/challenge$ ./run
```
<ins>What I understood:</ins> We can use * to autocomplete the remaining part of the directory

# Matching with ?
### Challenge Description: Change your directory to /challenge, but use the ? character instead of c and l in the argument to cd! Once you're there, run /challenge/run for the flag!
Solving: Using ? to substitute for each occurence of c and l I encounter in '/challenge' path.
Commands:
```
hacker@globbing~matching-with-:~$ cd /?ha??enge
hacker@globbing~matching-with-:/challenge$ ./run
```
<ins>What I understood:</ins> We can use ? to
