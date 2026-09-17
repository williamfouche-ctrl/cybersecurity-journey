Bandit levels 0-5 notes

**bandit 1**
- learned how to connect to a specific server port via ssh 
- what ssh is and how it gets used
- learned syntax for connecting (ssh {user}@{remote} and -p)
- cat {textfile} revealed its contents

**bandit 2**
- special characters (-) can not be directly cat because the system thinks its a command
- set the file name ./- else the system thinks its a command

**bandit 3**
- exit = leaves current session
- cd changes the directory (where you are)
- can use TAB to auto complete lines
- To read a file with spaces in its name, wrap the filename in quotes or use backslash: "./--spaces in this filename--" or ./--spaces \ in\ this\ filename--

**bandit 4**
- to run a command on every file in a folder = use ./* 
- * is a wildcard meaning everything in this folder

**bandit 5**
- find . = finds in current directory (the . represents were you are)
- -type f = finds only file types
- -size 1033c = c means bytes, looks for files of that size
- ! -executable = ! means not, so not executables
