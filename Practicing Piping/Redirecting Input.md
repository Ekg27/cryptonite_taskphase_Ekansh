# Redirecting Input
## Code:
```bash
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ rev < PWN
EGELLOC
hacker@piping~redirecting-input:~$ PWN > /challenge/run
ssh-entrypoint: /challenge/run: Permission denied
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{MYi2dtWwBNUriMw4dZpLxRhDlyP.dBzN1QDL3kzN0czW}
```
## Learning:
 I learnt how to Redirect Input in linux
## References:
 did on my own
