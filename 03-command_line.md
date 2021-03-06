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

>> 1. pwd  
>> 2. mkdir 'name_of_directory'
>> 3. rm -rf 'name_of_directory'
>> 4. touch 'name_of_file'
>> 5. rm 'name_of_file'
>> 6. mv 'old_name_of_file' 'new_name_of_file'
>> 7. ls -a 
>> 8. cp 'curent_path_to_file' 'path_to_file_where_you_want_it_to_be_copied'
>> 9. mkdir -p #only create directory if it doesnt exist
>> 10. rsync -av #copy a file but keep the original time stamp

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`
>> List all the files and subdirectories of the working directory   

`ls -a`  
>> List all the files and subdirectories of the	working	directory, including the hidden files that begin with a dot 

`ls -l`  
>> List all the files and subdirectories of the working directory in a list -- one entry per line  

`ls -lh`  
>>use unit suffixes: Byte, Kilobyte, Megabyte, Gigabyte, Terabyte and Petabyte in order reduce the number of digits to three or less using base 2 for sizes. Also, one entry per line 

`ls -lah`  
>> one entry per line, include files begining with '.', and include the unit suffixes 

`ls -t`  
>> sort by time modified 

`ls -Glp`  
>> Enable colorized output, one entry per line, write a slash after the files that are directories 


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -d 
>> Directories are listed as plain files (not searched recursively).

ls -ltr
>> Directories listed one per line, in reverse order of time modified (most recent modified file is last_

ls -L
>> Follow all symbolic links to final target and list the file or directory the link references rather than the link itself.

ls -p
>> Write a slash (`/') after each filename if that file is a directory.

ls -u 
>> Force unedited printing of non-graphic characters; this is the default when output is not to a terminal.
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> Please see https://www.howtoforge.com/tutorial/linux-xargs-command/

>> Acoording to that website: "reads data from standard input (stdin) and executes the command (supplied to it as an argument) one or more times based on the input read. Any blanks and spaces in the input are treated as delimiters, while blank lines are ignored"

 

