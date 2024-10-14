# Becoming root with Su
## Code:
```bash
hacker@permissions~the-suid-bit:~$ ls -l /challenge/getroot
-rwxr-xr-x 1 root root 155 Jul 12 10:30 /challenge/getroot
hacker@permissions~the-suid-bit:~$ chmod u+r /challenge/getroot
hacker@permissions~the-suid-bit:~$ chmod u+s /challenge/getroot
hacker@permissions~the-suid-bit:~$ /challenge/getroot
SUCCESS! You have set the suid bit on this program, and it is running as root!
Here is your shell...
root@permissions~the-suid-bit:~# cat /flag
pwn.college{EBlsIqdecrJltXooJIH7Da1mj8L.dNTM2QDL3kzN0czW}
root@permissions~the-suid-bit:~# client_loop: send disconnect: Broken pipe
ekansh_gupta@DESKTOP-VLR36O2:~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
hacker@users~becoming-root-with-su:~$ ls -l /challenge/getroot
ls: cannot access '/challenge/getroot': No such file or directory
hacker@users~becoming-root-with-su:~$ ls -l /usr/bin/su
-rwxr-xr-x 1 root root 67816 Apr  9  2024 /usr/bin/su
hacker@users~becoming-root-with-su:~$ su
Password:
root@users~becoming-root-with-su:/home/hacker# cat /flag
pwn.college{ov6SUnYmRqBlgCkIwydfAIdBMu1.dVTN0UDL3kzN0czW}
```
## Learning:
 I learnt how to use su command in linux
## References:
 did on my own
