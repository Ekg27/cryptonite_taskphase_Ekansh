# Help for builtins
## Code:
```bash
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "sBr322-A".
hacker@man~help-for-builtins:~$ /challenge/challenge --secret sBr322-A
ssh-entrypoint: /challenge/challenge: No such file or directory
hacker@man~help-for-builtins:~$ /challenge --secret sBr322-A
ssh-entrypoint: /challenge: Is a directory
hacker@man~help-for-builtins:~$ --secret sBr322-A
ssh-entrypoint: --secret: command not found
hacker@man~help-for-builtins:~$ --secret "sBr322-A"
ssh-entrypoint: --secret: command not found
hacker@man~help-for-builtins:~$ challenge --secret "sBr322-A"
Correct! Here is your flag!
pwn.college{sBr322-A-qio6a83aLhCmeajSiK.dRTM5QDL3kzN0czW}
```
## Learning:
 I learnt how to use help for builtins in linux
## References:
 did on my own
