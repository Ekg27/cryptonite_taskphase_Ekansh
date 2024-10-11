# Groups and Files
## Code:
```bash
hacker@permissions~groups-and-files:~$ ls -l /flag
-r--r----- 1 root root 58 Oct 11 14:28 /flag
hacker@permissions~groups-and-files:~$ chgrp hacker
chgrp: missing operand after ‘hacker’
Try 'chgrp --help' for more information.
hacker@permissions~groups-and-files:~$ chgrp hacker /flag
hacker@permissions~groups-and-files:~$ cat /flag
pwn.college{I1z7R2t9-MRJaEGvmBD653mu7Y3.dFzNyUDL3kzN0czW}
```
## Learning:
 I learnt about groups and files in linux
## References:
 did on my own
