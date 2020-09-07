Bash Examples 1
======

### Commands

+ `pwd`: Shows your current directory.
+ `ls`: Lists your files of your current directory.
+ `cd`: Moves between folders to Home.
 + `cd <directory>`: Moves to an specific directoy.
+ `mkdir <directory>`: Creates a new directory.
+ `rmdir <directory>`: Removes a directory.
+ `cat <file>`: Displays the content of a file.
+ `clear`: Clears the screen.
+ `history`: Displays the past commands used.
+ `rm <file>`: Removes a file.
+ `cp <file1> <file2>`: Copy a file.
+ `mv <file> <destination>`: Moves a file into a different directory.
 + `mv <file_name1> <file_name2>`: Renames a file.
+ `locate <word>`: Locates a file or directory by the specified word.
+ `nano <file>`: Creates a file and open the nano editor. 
+ `stat <file>`: Displays the stats of a file.
+ `man <command>`: Describes the function of an specified command.
+ `find .-name <file>`: Finds files starting with 'file' name.  


### Examples with 'find' command

- `find . -name "*.py"`
- `find /home -iname test.txt`
- `find /tmp -type d -empty`
- `find /home -iname MacBook`
- `find -name "*.xls" -type f`