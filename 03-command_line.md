# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > * `pwd` - show current working directory path
> > * `mkdir <directory>` - creating a directory
> > * `rm -r` - deleting a directory
> > * `touch <file>` - creating a file using `touch` command
> > * `rm <file>` - deleting a file
> > * `mv <old_file> <new_file>` - renaming a file
> > * `ls -la` - listing hidden files
> > * `cp <old_directory/file> <new_directory/file>` - copying a file from one directory to another
> > * `grep -rl "<text>" <directory>` - search for all files containing text in directory
> > * `cat <file>` - output all of the contents of file

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

> > * `ls` - list directory contents
> > * `ls -a`  - list all directory contents, even hidden files
> > * `ls -l`  - use long listing format
> > * `ls -lh`  - list files with human redable format
> > * `ls -lah`  - list all directory contents in a human redable long listing format
> > * `ls -t`  - list all directory contents by date/time
> > * `ls -Glp` - also uses the long listing format?

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > * `-c`	- displays files by file timestamp
> > * `-R`	- displays subdirectories
> > * `-F`	- flags filenames
> > * `-r`	- displays files by file access time
> > * `-1`	- displays each entry on a line

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` reads data from standard input and executes the command one or more times based on the input read. For example, you could use `xargs` this way:
> > `xargs find -name` - this will pass the find command along with its '-name' option as argument to xargs, and then pass the name of the file (or type of files) you want find to search as input through stdin.
