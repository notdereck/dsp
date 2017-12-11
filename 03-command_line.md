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

>> show current working directory path: pwd
>> creating a directory: mkdir [directory/folder name]
>> deleting a directory: rm -r [directory/folder name]
>> creating a file using `touch` command: touch [file name]
>> deleting a file: rm [file name]
>> renaming a file: mv [first file] [second file] (renames first file into second file]
>> listing hidden files: ls -al
>> copying a file from one directory to another: I think this is the same as renaming a file, mv [first file] [second file]
>> search for patterns in files: grep [pattern] [files]
>> change directory to X: cd X

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

>> ls : shows directory listing

>> ls -a : shows all file names, including names that begin with a dot

>> ls -l : shows 'long format', or more information like file size

>> ls -lh : 'long format' in human readable format 

>> ls -lah : same as ls -lh, but also shows file names that begin with a dot

>> ls -t : sorts by modification time, with newest coming first

>> ls -Glp : no group names printed in long listing, the p is the append / indicator to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>> -m displays the names as a comma-separated list

>> -d only shows directories

>> -p displays directories with '/'

>> -c displays files by timestamp

>> -R shows subdirectories too

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> xargs is supposed to build and execute command lines from standard output. It's helpful with other commands, like grep or cp. For example:

>> find . -name "*.txt" | xargs grep "booty" 

>> will find all text files in the specified directory and look for "booty"

 

