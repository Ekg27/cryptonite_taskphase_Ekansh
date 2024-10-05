# Matching with [ ]
## Code:
```bash
hacker@globbing~matching-with-:/challenge$ cd /challenge/files
hacker@globbing~matching-with-:/challenge/files$ file_[bash]
ssh-entrypoint: file_a: command not found
hacker@globbing~matching-with-:/challenge/files$ ls
file_a  file_c  file_e  file_g  file_i  file_k  file_m  file_o  file_q  file_s  file_u  file_w  file_y
file_b  file_d  file_f  file_h  file_j  file_l  file_n  file_p  file_r  file_t  file_v  file_x  file_z
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bash]
You got it! Here is your flag!
pwn.college{QbUQzP5pdoOeXGy5nYxKKax8n3K.dNjM4QDL3kzN0czW}
```
## Learning:
 I learnt how to use [] commands in linux
## References:
 did on my own
