# CSE 15L Lab Report 1
## Empty Commands
## Empty `cat` Command
![Image](empty_cat.png)
* Absolute directory was /c/Users/kurom
* There was nothing to join with the `cat` command hence why the output comes out completely blank. Yet, it's also why the terminal doesn't just return a new command, seeing as pressing 'enter' on a blank space outputs another blank space, entering 'e' returns another 'e', etc.
* No, I don't think this is necessarily an error. Not what we want, but not an error either.

Empty `cd` Command
---
![Image](empty_cd.png)
* Absolute directory was /c/Users/kurom
* Without an argument, your output is just the home directory as that's where you already start off. You're basically just changing directory to nowhere.
* Not an error.

Empty `ls` Command
---
![Image](empty_ls.png)
* Absolute directory was /c/Users/kurom
* Since the `ls` command lists out contents, these are what appear on the output since these are contents inside the home directory.
* Not an error.

## Directory Commands
## Directory `cat` Command
![Image](directory_cat.png)
* Absolute directory was /c/Users/kurom
* The `cat` command basically prints out the contents of the file. Since this is a directory and not a file, the output instead prints out this message.
* Not an error.

Directory `cd` Command
---
![Image](directory_cd.png)
* Absolute directory was /c/Users/kurom
* Since `cd` changes directory, this command accesses the lecture1 directory in order to then run commands on the contents inside.
* Not an error.

Directory `ls` Command
---
![Image](directory_ls.png)
* Absolute directory was /c/Users/kurom
* The `ls` command lists out what's inside the directory. Since the lecture1 folder contains these files and more directories, they show up in the output.
* Not an error.

## File Commands
## File `cat` Command
![Image](file_cat.png)
* Absolute directory was /c/Users/kurom/lecture1/messages
* Since the `cat` command prints out the contents of a file and this is a file, the output is the actual message 'Hallo Welt!`
* Not an error.

File `cd` Command
---
![Image](file_cd.png)
* Absolute directory was /c/Users/kurom/lecture1/messages
* Since `cd` is meant to change directory and there is no further directory, the output points out the argument is not a directory.
* It is an error. `cd` stands for "change directory", in which this file isn't one.

File `ls` Command
---
![Image](file_ls.png)
* Absolute directory was /c/Users/kurom/lecture1/messages
* Since the file is not a directory, all the output can list out in an `ls` command is itself.
* Not an error.
