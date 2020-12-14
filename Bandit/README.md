![image-20200922150506257](./README.assets/image-20200922150506257.png)

# OverTheWire | Bandit

Writeup by Andrew Jerry | 22 September 2020

# Level 0

## Level Goal

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is **bandit.labs.overthewire.org**, on port 2220. The username is **bandit0** and the password is **bandit0**. Once logged in, go to the [Level 1](https://overthewire.org/wargames/bandit/bandit1.html) page to find out how to beat Level 1.

## Commands you may need to solve this level

ssh

## Solution

![image-20200922150803744](./README.assets/image-20200922150803744.png)

# Bandit Level 0 → Level 1

## Level Goal

The password for the next level is stored in a file called **readme** located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

## Commands you may need to solve this level

ls, cd, cat, file, du, find

## Solution

![image-20200922151004797](./README.assets/image-20200922151004797.png)

Password for next level:

boJ9jbbUNNfktd78OOpsqOltutMc3MY1

# Bandit Level 1 → Level 2

## Level Goal

The password for the next level is stored in a file called **-** located in the home directory

## Commands you may need to solve this level

ls, cd, cat, file, du, find

## Helpful Reading Material

- [Google Search for “dashed filename”](https://www.google.com/search?q=dashed+filename)
- [Advanced Bash-scripting Guide - Chapter 3 - Special Characters](http://tldp.org/LDP/abs/html/special-chars.html)

## Solution

![image-20200922151307798](./README.assets/image-20200922151307798.png)

Password for next level:

CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

# Bandit Level 2 → Level 3

## Level Goal

The password for the next level is stored in a file called **spaces in this filename** located in the home directory

## Commands you may need to solve this level

ls, cd, cat, file, du, find

## Helpful Reading Material

- [Google Search for “spaces in filename”](https://www.google.com/search?q=spaces+in+filename)

## Solution

![image-20200922151834404](./README.assets/image-20200922151834404.png)

Password for next level:

UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

# Bandit Level 3 → Level 4

## Level Goal

The password for the next level is stored in a hidden file in the **inhere** directory.

## Commands you may need to solve this level

ls, cd, cat, file, du, find

## Solution

![image-20200922151955339](./README.assets/image-20200922151955339.png)

Password for next level:

pIwrPrtPN36QITSp3EQaw936yaFoFgAB

# Bandit Level 4 → Level 5

## Level Goal

The password for the next level is stored in the only human-readable file in the **inhere** directory. Tip: if your terminal is messed up, try the “reset” command.

## Commands you may need to solve this level

ls, cd, cat, file, du, find

## Solution

![image-20200922153004928](./README.assets/image-20200922153004928.png)

Password for next level:

koReBOKuIDDepwhWk7jZC0RTdopnAYKh

# Bandit Level 5 → Level 6

## Level Goal

The password for the next level is stored in a file somewhere under the **inhere** directory and has all of the following properties:

- human-readable
- 1033 bytes in size
- not executable

## Commands you may need to solve this level

ls, cd, cat, file, du, find

## Solution

![image-20200922153819821](./README.assets/image-20200922153819821.png)

Password for next level:

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

# Bandit Level 6 → Level 7

## Level Goal

The password for the next level is stored **somewhere on the server** and has all of the following properties:

- owned by user bandit7
- owned by group bandit6
- 33 bytes in size

## Commands you may need to solve this level

ls, cd, cat, file, du, find, grep

## Solution

![image-20200922154108724](./README.assets/image-20200922154108724.png)

Password for next level:

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

# Bandit Level 7 → Level 8

## Level Goal

The password for the next level is stored in the file **data.txt** next to the word **millionth**

## Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

## Solution

![image-20200922154313999](./README.assets/image-20200922154313999.png)

Password for next level:

cvX2JJa4CFALtqS87jk27qwqGhBM9plV

# Bandit Level 8 → Level 9

## Level Goal

The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once

## Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

## Helpful Reading Material

- [Piping and Redirection](https://ryanstutorials.net/linuxtutorial/piping.php)

## Solution

![image-20200922172559359](./README.assets/image-20200922172559359.png)

Password for next level:

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

# Bandit Level 9 → Level 10

## Level Goal

The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.

## Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

## Solution

![image-20200922172741837](./README.assets/image-20200922172741837.png)

Password for next level:

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

# Bandit Level 10 → Level 11

## Level Goal

The password for the next level is stored in the file **data.txt**, which contains base64 encoded data

## Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

## Helpful Reading Material

- [Base64 on Wikipedia](https://en.wikipedia.org/wiki/Base64)

## Solution

![image-20200922172853234](./README.assets/image-20200922172853234.png)

Password for next level:

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

# Bandit Level 11 → Level 12

## Level Goal

The password for the next level is stored in the file **data.txt**, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

## Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

## Helpful Reading Material

- [Rot13 on Wikipedia](https://en.wikipedia.org/wiki/Rot13)

## Solution

![image-20200922173250595](./README.assets/image-20200922173250595.png)

Password for next level:

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

# Bandit Level 12 → Level 13

## Level Goal

The password for the next level is stored in the file **data.txt**, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)

## Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd, mkdir, cp, mv, file

## Helpful Reading Material

- [Hex dump on Wikipedia](https://en.wikipedia.org/wiki/Hex_dump)

## Solution

![image-20200922175726096](./README.assets/image-20200922175726096.png)

![image-20200922175855027](./README.assets/image-20200922175855027.png)

![image-20200922175934515](./README.assets/image-20200922175934515.png)

![image-20200922180058617](./README.assets/image-20200922180058617.png)

![image-20200922180140949](./README.assets/image-20200922180140949.png)

Password for next level:

 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

# Bandit Level 13 → Level 14

## Level Goal

The password for the next level is stored in **/etc/bandit_pass/bandit14 and can only be read by user bandit14**. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. **Note:** **localhost** is a hostname that refers to the machine you are working on

## Commands you may need to solve this level

ssh, telnet, nc, openssl, s_client, nmap

## Helpful Reading Material

- [SSH/OpenSSH/Keys](https://help.ubuntu.com/community/SSH/OpenSSH/Keys)

## Solution

![image-20200923104641871](./README.assets/image-20200923104641871.png)

![image-20200923104715766](./README.assets/image-20200923104715766.png)

![image-20200923104601076](./README.assets/image-20200923104601076.png)

Password for next level:

4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e

# Bandit Level 14 → Level 15

## Level Goal

The password for the next level can be retrieved by submitting the password of the current level to **port 30000 on localhost**.

## Commands you may need to solve this level

ssh, telnet, nc, openssl, s_client, nmap

## Helpful Reading Material

- [How the Internet works in 5 minutes (YouTube)](https://www.youtube.com/watch?v=7_LPdttKXPc) (Not completely accurate, but good enough for beginners)
- [IP Addresses](http://computer.howstuffworks.com/web-server5.htm)
- [IP Address on Wikipedia](https://en.wikipedia.org/wiki/IP_address)
- [Localhost on Wikipedia](https://en.wikipedia.org/wiki/Localhost)
- [Ports](http://computer.howstuffworks.com/web-server8.htm)
- [Port (computer networking) on Wikipedia](https://en.wikipedia.org/wiki/Port_(computer_networking))

## Solution

![image-20200923132230514](./README.assets/image-20200923132230514.png)

Password for next level:

BfMYroe26WYalil77FoDi9qh59eK5xNr

# Bandit Level 15 → Level 16

## Level Goal

The password for the next level can be retrieved by submitting the password of the current level to **port 30001 on localhost** using SSL encryption.

**Helpful note: Getting “HEARTBEATING” and “Read R BLOCK”? Use -ign_eof and read the “CONNECTED COMMANDS” section in the manpage. Next to ‘R’ and ‘Q’, the ‘B’ command also works in this version of that command…**

## Commands you may need to solve this level

ssh, telnet, nc, openssl, s_client, nmap

## Helpful Reading Material

- [Secure Socket Layer/Transport Layer Security on Wikipedia](https://en.wikipedia.org/wiki/Secure_Socket_Layer)
- [OpenSSL Cookbook - Testing with OpenSSL](https://www.feistyduck.com/library/openssl-cookbook/online/ch-testing-with-openssl.html)

## Solution

![image-20200923133119328](./README.assets/image-20200923133119328.png)

![image-20200923133142784](./README.assets/image-20200923133142784.png)

Password for next level:

cluFn7wTiGryunymYOu4RcffSxQluehd



# Bandit Level 16 → Level 17

## Level Goal

The credentials for the next level can be retrieved by submitting the password of the current level to **a port on localhost in the range 31000 to 32000**. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.

## Commands you may need to solve this level

ssh, telnet, nc, openssl, s_client, nmap

## Helpful Reading Material

- [Port scanner on Wikipedia](https://en.wikipedia.org/wiki/Port_scanner)

## Solution

![image-20200924153646556](./README.assets/image-20200924153646556.png)

![image-20200924153706153](./README.assets/image-20200924153706153.png)

![image-20200924153725142](./README.assets/image-20200924153725142.png)

Password for next level:

-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----





# Bandit Level 17 → Level 18

## Level Goal

There are 2 files in the homedirectory: **passwords.old and passwords.new**. The password for the next level is in **passwords.new** and is the only line that has been changed between **passwords.old and passwords.new**

**NOTE: if you have solved this level and see ‘Byebye!’ when trying to log into bandit18, this is related to the next level, bandit19**

## Commands you may need to solve this level

cat, grep, ls, diff

## Solution

![image-20200924154146357](./README.assets/image-20200924154146357.png)

Password for next level:

kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd

# Bandit Level 18 → Level 19

## Level Goal

The password for the next level is stored in a file **readme** in the homedirectory. Unfortunately, someone has modified **.bashrc** to log you out when you log in with SSH.

## Commands you may need to solve this level

ssh, ls, cat

## Solution

![image-20200924154651784](./README.assets/image-20200924154651784.png)

Password for next level:

IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x



# Bandit Level 19 → Level 20

## Level Goal

To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.

## Helpful Reading Material

- [setuid on Wikipedia](https://en.wikipedia.org/wiki/Setuid)

## Solution

![image-20200924155125827](./README.assets/image-20200924155125827.png)

![image-20200924155145951](./README.assets/image-20200924155145951.png)

![image-20200924155200572](./README.assets/image-20200924155200572.png)

Password for next level:

GbKksEFF4yrVs6il55v6gwY5aVje5f0j

# Bandit Level 20 → Level 21

## Level Goal

There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).

**NOTE:** Try connecting to your own network daemon to see if it works as you think

## Commands you may need to solve this level

ssh, nc, cat, bash, screen, tmux, Unix ‘job control’ (bg, fg, jobs, &, CTRL-Z, …)

## Solution

![image-20200924155822624](./README.assets/image-20200924155822624.png)

![image-20200924155734108](./README.assets/image-20200924155734108.png)

![image-20200924155840668](./README.assets/image-20200924155840668.png)

![image-20200924155900817](./README.assets/image-20200924155900817.png)

![image-20200924155917912](./README.assets/image-20200924155917912.png)

Password for next level:

gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr

# Bandit Level 21 → Level 22

## Level Goal

A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

## Commands you may need to solve this level

cron, crontab, crontab(5) (use “man 5 crontab” to access this)

## Solution

![image-20200924205244502](./README.assets/image-20200924205244502.png)

![image-20200924205310320](./README.assets/image-20200924205310320.png)

![image-20200924205136759](./README.assets/image-20200924205136759.png)



Password for next level:

Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI

# Bandit Level 22 → Level 23

## Level Goal

A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

**NOTE:** Looking at shell scripts written by other people is a very useful skill. The script for this level is intentionally made easy to read. If you are having problems understanding what it does, try executing it to see the debug information it prints.

## Commands you may need to solve this level

cron, crontab, crontab(5) (use “man 5 crontab” to access this)

## Solution

![image-20200924212606892](./README.assets/image-20200924212606892.png)

![image-20200924212541611](./README.assets/image-20200924212541611.png)

![image-20200924212440867](./README.assets/image-20200924212440867.png)

![image-20200924212418441](./README.assets/image-20200924212418441.png)

Password for next level:

jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n

# Bandit Level 23 → Level 24

## Level Goal

A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

**NOTE:** This level requires you to create your own first shell-script. This is a very big step and you should be proud of yourself when you beat this level!

**NOTE 2:** Keep in mind that your shell script is removed once executed, so you may want to keep a copy around…

## Commands you may need to solve this level

cron, crontab, crontab(5) (use “man 5 crontab” to access this)

## Solution



Password for next level:

# Bandit Level 24 → Level 25

## Level Goal

A daemon is listening on port 30002 and will give you the password for bandit25 if given the password for bandit24 and a secret numeric 4-digit pincode. There is no way to retrieve the pincode except by going through all of the 10000 combinations, called brute-forcing.

## Solution



Password for next level:

# Bandit Level 25 → Level 26

## Level Goal

Logging in to bandit26 from bandit25 should be fairly easy… The shell for user bandit26 is not **/bin/bash**, but something else. Find out what it is, how it works and how to break out of it.

## Commands you may need to solve this level

ssh, cat, more, vi, ls, id, pwd

## Solution



Password for next level:

# Bandit Level 26 → Level 27

## Level Goal

Good job getting a shell! Now hurry and grab the password for bandit27!

## Commands you may need to solve this level

ls

## Solution



Password for next level:

# Bandit Level 27 → Level 28

## Level Goal

There is a git repository at `ssh://bandit27-git@localhost/home/bandit27-git/repo`. The password for the user `bandit27-git` is the same as for the user `bandit27`.

Clone the repository and find the password for the next level.

## Commands you may need to solve this level

git

## Solution



Password for next level:

# Bandit Level 28 → Level 29

## Level Goal

There is a git repository at `ssh://bandit28-git@localhost/home/bandit28-git/repo`. The password for the user `bandit28-git` is the same as for the user `bandit28`.

Clone the repository and find the password for the next level.

## Commands you may need to solve this level

git

## Solution



Password for next level:

# Bandit Level 29 → Level 30

## Level Goal

There is a git repository at `ssh://bandit29-git@localhost/home/bandit29-git/repo`. The password for the user `bandit29-git` is the same as for the user `bandit29`.

Clone the repository and find the password for the next level.

## Commands you may need to solve this level

git

## Solution



Password for next level:

# Bandit Level 30 → Level 31

## Level Goal

There is a git repository at `ssh://bandit30-git@localhost/home/bandit30-git/repo`. The password for the user `bandit30-git` is the same as for the user `bandit30`.

Clone the repository and find the password for the next level.

## Commands you may need to solve this level

git

## Solution



Password for next level:

# Bandit Level 31 → Level 32

## Level Goal

There is a git repository at `ssh://bandit31-git@localhost/home/bandit31-git/repo`. The password for the user `bandit31-git` is the same as for the user `bandit31`.

Clone the repository and find the password for the next level.

## Commands you may need to solve this level

git

## Solution



Password for next level:

# Bandit Level 32 → Level 33

After all this `git` stuff its time for another escape. Good luck!

## Commands you may need to solve this level

sh, man

## Solution



Password for next level:

# Bandit Level 33 → Level 34

**At this moment, level 34 does not exist yet.**



