# Linux Luminarium

## Comprehending Commands

So far, we've told you which files to interact with. But directories can have lots of files (and other directories) inside them, and we won't always be here to tell you their names. You'll need to learn to list their contents using the ls command!

ls will list files in all the directories provided to it as arguments, and in the current directory if no arguments are provided. Observe:

hacker@dojo:~$ ls /challenge
run
hacker@dojo:~$ ls
Desktop    Downloads  Pictures  Templates
Documents  Music      Public    Videos
hacker@dojo:~$ ls /home/hacker
Desktop    Downloads  Pictures  Templates
Documents  Music      Public    Videos
hacker@dojo:~$
In this challenge, we've named /challenge/run with some random name! List the files in /challenge to find it.

### Terminal output

`ls /challenge`

`/challenge/22342-renamed-run-19328`

## Flag

> pwn.college{00_D7OkQh87OWQcL99n8R-hrPnG.QX4IDO0wiM3MjMwEzW}
