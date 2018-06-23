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

> > pwd   * show current working directory path
mkdir * creating a directory
rmdir * deleting a directory
touch * creating a file using `touch` command
rm    * deleting a file
mv same/path * renaming a file
ls -a * listing hidden files
cp filename to_path * copying a file from one directory to another
ls -u * Displays files by the file access time.
tac * concatenate and print files in reverse
cat * concatenate files and print on the standard output

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

> > `ls`  lists the files in a directory
`ls -a`   lists all file, including hidden files
`ls -l`   provides the long list of attributes
`ls -lh`  shows long list with print sizes in human readable format
`ls -lah` shows long list with print sizes of all files (including hidden) in human readable format
`ls -t`   lists files sorted by modification time, newest first
`ls -Glp` lists files without Group with long list and appends path with slash

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 'ls -u' Displays files by the file access time.
'ls -L' * symbolic link
'ls *[0-9]*' * Displays a list of files that contain a digit
'ls [^a-k]*' Displays files that do Not begin with letters l - m.
'ls -e'   Prints the Access control list for the file, if present, in long format.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs repeats a procedure on each item of a list.

 

