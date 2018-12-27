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

> > REPLACE THIS TEXT WITH YOUR RESPONSE

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

> >	ls: lists directory contents of files and directories
	ls -a: list all files including hidden files 
	ls -l: list with long format - show permissions
	ls -lh: list with long format, with readable file size
	ls -lah: list with long format, with readable file size, including
		 hidden files
	ls -t: list sorted by timestamp, newest files first
	ls -Glp: list with long format, displays directories with / and 
		colored blue. 

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -d: displays only directories 
    ls -R: displays subdirectories 
    ls -r: displays contents in reverse order
    ls -m: displays contents as comma-separated list
    ls -1: displays each entry on a line

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs reads items from standard input and creates multiple arguments upon which to execute a command. For example:
    $ find . -name "*.pdf" | xargs rm would find all the PDFs in the current directory, and pass the "rm" command to each file.  

 

