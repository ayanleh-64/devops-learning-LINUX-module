# Level 1 - 2

## Goal:
The password for the next level is stored in a file called ```-``` located in the home directory
## Steps I Took:
- Once I logged on i used ```ls``` to check the contents of the directory
- I then attempted to use the command```cat -``` but this did not work as whatever i typed in the terminal was read and printed back to me.
- Therefore i used the ```man cat``` command to check the man page and realised that in linux ```-``` is treated as standard input rather than a filename, which is why ```cat -``` waited for keyboard input instead of reading the file.
- Finally i used ```cat ./-``` to force the shell to treat ```-``` as a filename, read the file and acquire the password.
### Password Found: 
```263JGJPfgU6LtdEvgfWU1XP5yac29mFx```

![Screenshot](bandit1-2.png).




