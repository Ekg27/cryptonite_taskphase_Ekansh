## Code:
```bash
hacker@permissions~changing-file-ownership:~$ ls -l
total 24
-rw-r--r-- 1 hacker hacker   4 Oct  7 08:42 COLLEGE
-rw-r--r-- 1 hacker hacker   8 Oct  7 14:02 PWN
-rw-r--r-- 1 root   hacker  58 Oct  2 11:26 a
lrwxrwxrwx 1 hacker hacker  18 Oct  3 12:58 catflag -> /challenge/catflag
-rw-r--r-- 1 hacker hacker   0 Oct  5 04:58 challenge
-rw-r--r-- 1 hacker hacker 829 Oct  7 13:44 instructions
-rw-r--r-- 1 hacker hacker  93 Oct  7 13:44 myflag
lrwxrwxrwx 1 hacker hacker  18 Oct  3 13:28 not-the-file -> /challenge/catflag
lrwxrwxrwx 1 hacker hacker   5 Oct  3 13:32 not-the-flag -> /flag
-rw-r--r-- 1 root   hacker  77 Oct  7 14:33 out
-rw-r--r-- 1 hacker hacker   0 Oct  9 13:56 tee
-rw-r--r-- 1 hacker hacker   0 Oct  7 13:40 the-flag
hacker@permissions~changing-file-ownership:~$ chown hacker /flag
hacker@permissions~changing-file-ownership:~$ cat /flag
pwn.college{wbp1KzlEBroxMfCL72Dj54op8UW.dFTM2QDL3kzN0czW}
```
## Learning:
 I learnt how to Change file owner in linux
## References:
 did on my own
