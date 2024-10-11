# Listing processes
## Code:
```bash
hacker@processes~listing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 10:57 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /ru
root           7       1  0 10:57 ?        00:00:00 /run/dojo/bin/sleep 6h
root          68       1  0 10:57 ?        00:00:00 /challenge/14061-run-14974
root          72      68  0 10:57 ?        00:00:00 sleep 6h
hacker        73       0  0 10:58 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker        90      73  0 10:58 pts/0    00:00:00 ps -ef
hacker@processes~listing-processes:~$ ps -aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.0   1056   640 ?        Ss   10:57   0:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bi
root           7  0.0  0.0   5052  2560 ?        S    10:57   0:00 /run/dojo/bin/sleep 6h
root          68  0.0  0.0   4132  2560 ?        S    10:57   0:00 /challenge/14061-run-14974
root          72  0.0  0.0   2744  1280 ?        S    10:57   0:00 sleep 6h
hacker        73  0.1  0.0   5376  3840 pts/0    Ss   10:58   0:00 /run/dojo/bin/ssh-entrypoint
hacker        91  0.0  0.0   7868  3200 pts/0    R+   10:59   0:00 ps -aux
hacker@processes~listing-processes:~$ ./challenge/14061-run-14974
ssh-entrypoint: ./challenge/14061-run-14974: Not a directory
hacker@processes~listing-processes:~$ /challenge/14061-run-14974
Yahaha, you found me! Here is your flag:
pwn.college{YG0urlHhLD69N0sRMsJ1HEHLNBz.dhzM4QDL3kzN0czW}
Now I will sleep for a while (so that you could find me with 'ps').
```
## Learning:
 I learnt how to list processes in linux
## References:
 did on my own
