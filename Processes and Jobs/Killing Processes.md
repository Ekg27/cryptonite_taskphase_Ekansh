# Killing Processes
## Code:
```bash
hacker@processes~killing-processes:~$ ps
    PID TTY          TIME CMD
     75 pts/0    00:00:00 ssh-entrypoint
     92 pts/0    00:00:00 ps
hacker@processes~killing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 11:05 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /ru
root           7       1  0 11:05 ?        00:00:00 /run/dojo/bin/sleep 6h
root          71       1  0 11:05 ?        00:00:00 su -c /challenge/.launcher hacker
hacker        73      71  0 11:05 ?        00:00:00 /challenge/dont_run
hacker        74      73  0 11:05 ?        00:00:00 sleep 6h
hacker        75       0  0 11:06 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker        93      75  0 11:07 pts/0    00:00:00 ps -ef
hacker@processes~killing-processes:~$ ps -e
    PID TTY          TIME CMD
      1 ?        00:00:00 docker-init
      7 ?        00:00:00 /run/dojo/bin/s
     71 ?        00:00:00 su
     73 ?        00:00:00 bash
     74 ?        00:00:00 sleep
     75 pts/0    00:00:00 ssh-entrypoint
     94 pts/0    00:00:00 ps
hacker@processes~killing-processes:~$ kill 73
hacker@processes~killing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 11:05 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /ru
root           7       1  0 11:05 ?        00:00:00 /run/dojo/bin/sleep 6h
hacker        74       1  0 11:05 ?        00:00:00 sleep 6h
hacker        75       0  0 11:06 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker        95      75  0 11:08 pts/0    00:00:00 ps -ef
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{oew01f7sXxJry9EFyKaAWaZwUdC.dJDN4QDL3kzN0czW}
```
## Learning:
 I learnt how to kill processes in linux
## References:
 did on my own
