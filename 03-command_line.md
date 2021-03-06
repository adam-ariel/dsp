# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > pwd, mkdir, rmdir, touch, rm, mv, ls -a, cp, cd (changes directory), man (manual: explains what a certain command does)

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > lists files in your working directory, includes directories that start with a '.', includes details about files, writes sizes in prefixed form, all the above stuff, sort by time modified, use color for long format with dirs indicated by '*/'

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > -r reverses order, -S sorts by size, -U sorts by creation date, -1 forces one item per line, -m output as csv

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > I read a bunch about this and honestly I'm still a bit confused. It's something like a distributive property for inputs to a function if you want to apply the function manually to each input because the function can't handle distributing itself for whatever reason (perhaps overload). 
 

