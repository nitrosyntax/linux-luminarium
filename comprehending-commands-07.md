# Linux Luminarium

## Comprehending Commands

Files are all around you. Like candy wrappers, there'll eventually be too many of them. In this level, we'll learn to clean up!

In Linux, you remove files with the rm command, as so:

hacker@dojo:~$ touch PWN
hacker@dojo:~$ touch COLLEGE
hacker@dojo:~$ ls
COLLEGE     PWN
hacker@dojo:~$ rm PWN
hacker@dojo:~$ ls
COLLEGE
hacker@dojo:~$
Let's practice. This challenge will create a delete_me file in your home directory! Delete it, then run /challenge/check, which will make sure you've deleted it and then give you the flag!

### Terminal output

`rm delete_me`

`/challenge/check`

## Flag

> pwn.college{wAws8OsHBNAOGHxfp1tGo2fPb7T.QX2kDM1wiM3MjMwEzW}
