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

> > 
1.  pwd = show current working directory path
2.  mkdir = creating a directory
3.  rm -r = deleting a directory (and all of its child directories)
4.  touch = creating a file using `touch` command
5.  rm = deleting a file
6.  mv = renaming a file ("move" to new file name)
7.  ls -a = listing hidden files
8.  cp =  copying a file from one directory to another
9.  cd = change directory
10. cd.. = move up one directory
11. ls -l = listing files in long format
12. ls -t = listing files in ordered format
13. * = wildcard
14. ' > ' = redirects stdin to stdout (overwrites)
15. ' >> ' = redirects by appending (does not overwrite)
16. cat = outputs the contents of a file to the terminal
17. | = pipe, or command to command redirection
18. sort = sorts alphabetically
19. uniq = filters adjacent duplicate lines
20. grep = global regular expression print (searches for a text pattern and outputs it)
21. grep -i = case insentive grep
22. sed = "Find and Replace" stream editor (searches for text, modifies and replaces the first instance in a line)
23. g = global (can be used above to replace all instances)
24. clear = clears terminal window
25. source = activates changes without closing terminal and starting a new session
26. alias = creates keyboard shortcuts for commonly used commands
27. export = makes variable available to all child sessions initiated from current session
28. PSI = defines the makeup and style of the command prompt
29. HOME = displays path of home directory
30. PATH = lists which directories contain scripts
31. env = return list of environment variables
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

`ls`  - lists all files in a directory

`ls -a`  - displays all contents, including hidden files

`ls -l`  - displays the long format listing

`ls -lh`  - displays human readable sizes of long formatted listing

`ls -lah` - displays all contents, including hidden files, in human readable sizes of long formatted listing

`ls -t`  - displays the newest files first based on timestamp

`ls -Glp`- displays directories with slash ("/") in long listing format without the Group names


### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 

`ls -c`	Displays files by file timestamp

`ls -d`	Displays only directories

`ls -m`	Displays the names as a comma-separated list

`ls -r`	Displays files in reverse order

`ls -R`	Displays subdirectories as well

> >

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

 

