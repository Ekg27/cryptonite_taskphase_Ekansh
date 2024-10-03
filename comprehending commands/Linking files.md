# Linking files
## Code:
```bash
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
ln: failed to create symbolic link '/home/hacker/not-the-flag': File exists
hacker@commands~linking-files:~$ ln -s /challenge/catflag /home/hacker/not-the-flag
ln: failed to create symbolic link '/home/hacker/not-the-flag': File exists
hacker@commands~linking-files:~$ rm /home/hacker/not-the-flag
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{MbWKVsya6drFXgkxnir-_5laFsf.dlTM1UDL3kzN0czW}
```
## Learning:
 I learnt how to find link files in linux
## References:
 did on my own
