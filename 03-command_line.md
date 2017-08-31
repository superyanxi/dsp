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

> > **pwd** show current working directory path
    ---
    **mkdir** creating a directory
    ---
    **rm -r** deleting a directory
    ---
    **touch** creating a file using `touch` command
    ---
    **rm** deleting a file
    ---
    **mv** renaming a file
    ---
    **ls -a** listing hidden Files
    ---
    **cp [file] [dir]** copying a file from one directory to another
    ---
    **ls -l** lists all contents in long format
    ---
    **ls -t** orders files and directories by the time they were last modified
    ---
    :fireworks:

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

> >
    `ls` lists all files and directories in the     working    directory.
    ---
    `ls -a` lists all contents of a directory, including hidden files and directories
    ---
    `ls -l` lists all contents in long format  
    ---
    `ls -lh` Long listing with Human readable file sizes
    ---
    `ls -lah`   Long listing with Human readable file sizes and lists all contents of a directory, including hidden files and directories
    ---
    `ls -t` list orders files and directories by the time they were last modified
    ---
    `ls -Glp`  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > **ls -F** Flags filenames.
    ---
    **ls -m** Displays the names as a comma-separated list.
    ---
    **ls -u** Displays files by the file access time.
    ---
    **ls -x** Displays files as rows across the screen.
    ---
    **ls -b** Displays nonprinting characters in octal.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs command is designed to construct argument lists and invoke other utility. xargs reads items from the standard input or pipes, delimited by blanks or newlines, and executes the command one or more times with any initial-arguments followed by items read from standard input.
