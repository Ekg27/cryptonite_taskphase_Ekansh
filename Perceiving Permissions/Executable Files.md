# Executable Files
## Code:
```bash
hacker@permissions~executable-files:~$ ls -l /challenge/run
-r--r--r-- 1 hacker hacker 32 Jul  4 06:37 /challenge/run
hacker@permissions~executable-files:~$ chmod u+x /challenge/run
hacker@permissions~executable-files:~$ ls -l
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
hacker@permissions~executable-files:~$ ls -l /challenge/run
-r-xr--r-- 1 hacker hacker 32 Jul  4 06:37 /challenge/run
hacker@permissions~executable-files:~$  /challenge/run
Successful execution! Here is your flag:
pwn.college{AmdqajGQ-3lspUbQGObmMLvLdYr.dJTM2QDL3kzN0czW}
```
## Learning:
 I learnt how to give permission to Execute Files in linux
## References:
 did on my own
