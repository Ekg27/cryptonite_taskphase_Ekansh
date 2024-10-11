# Fun with group names
## Code:
```bash
hacker@permissions~fun-with-groups-names:~$ ls -l
total 24
-rw-r--r-- 1 hacker grp29415   4 Oct  7 08:42 COLLEGE
-rw-r--r-- 1 hacker grp29415   8 Oct  7 14:02 PWN
-rw-r--r-- 1 root   grp29415  58 Oct  2 11:26 a
lrwxrwxrwx 1 hacker grp29415  18 Oct  3 12:58 catflag -> /challenge/catflag
-rw-r--r-- 1 hacker grp29415   0 Oct  5 04:58 challenge
-rw-r--r-- 1 hacker grp29415 829 Oct  7 13:44 instructions
-rw-r--r-- 1 hacker grp29415  93 Oct  7 13:44 myflag
lrwxrwxrwx 1 hacker grp29415  18 Oct  3 13:28 not-the-file -> /challenge/catflag
lrwxrwxrwx 1 hacker grp29415   5 Oct  3 13:32 not-the-flag -> /flag
-rw-r--r-- 1 root   grp29415  77 Oct  7 14:33 out
-rw-r--r-- 1 hacker grp29415   0 Oct  9 13:56 tee
-rw-r--r-- 1 hacker grp29415   0 Oct  7 13:40 the-flag
hacker@permissions~fun-with-groups-names:~$ ls -l /flag
-r--r----- 1 root root 58 Oct 11 14:31 /flag
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp29415) groups=1000(grp29415)
hacker@permissions~fun-with-groups-names:~$ chgrp grp29415
chgrp: missing operand after ‘grp29415’
Try 'chgrp --help' for more information.
hacker@permissions~fun-with-groups-names:~$ chgrp grp29415 /flag
hacker@permissions~fun-with-groups-names:~$ cat /flag
pwn.college{AaDMs0_ITz_r7kIZItTkgK6o-84.dJzNyUDL3kzN0czW}
```
## Learning:
 I learnt how to use cat in linux
## References:
 did on my own
