# Linux Luminarium

## Comprehending Commands

Sometimes, the files that you might cat out are too big. Luckily, we have the grep command to search for the contents we need! We'll learn it in this challenge.

There are many ways to grep, and we'll learn on way here:

hacker@dojo:~$ grep SEARCH_STRING /path/to/file
Invoked like this, grep will search the file for lines of text containing SEARCH_STRING and print them to the console.

In this challenge, I've put a hundred thousand lines of text into the /challenge/data.txt file. Grep it for the flag!

HINT: The flag always starts with the text pwn.college.

### Terminal output

`grep pwn.college /challenge/data.txt`

## Flag

> pwn.college{AMKyXiq1pkDN8bBHgZOPFLcaka4.QX3EDO0wiM3MjMwEzW}
