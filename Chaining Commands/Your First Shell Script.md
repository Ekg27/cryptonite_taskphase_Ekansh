# Your First Shell Script
## Code:
```bash
hacker@chaining~your-first-shell-script:~$ touch x.sh
hacker@chaining~your-first-shell-script:~$ /challenge/pwn >> x.sh
It looks like you may have chained the pwn command with a pipe or other input
redirection method. In this level, you must script the commands to run one
after the other, without piping or redirection!
hacker@chaining~your-first-shell-script:~$ echo /challenge/pwn >> x.sh
hacker@chaining~your-first-shell-script:~$ echo /challenge/college >> x.sh
hacker@chaining~your-first-shell-script:~$ bash x.sh
Great job, you've written your first shell script! Here is the flag:
pwn.college{oT6Unz-3oKNIcx14FxvnHgP8wKZ.dFzN4QDL3kzN0czW}
```
## Learning:
 I learnt how to write shell script in linux
## References:
 did on my own
