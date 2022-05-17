# Summer-Camp-RIG-2022

### Session : Linux by Erin

- `pwd` : Current working directory (eg : /home/erin/Documents )
- `ls` : List files in directory
- `clear` : Clear the terminal
- `cd` : Change directory (eg cd ~/Documents , ~ means home directory )
- `cd ..` : Navigate to a directory behind ( /home/erin/hello ---> /home/erin )
- `cd -` : Navigate to previous directory
- `mkdir Linus_hands_on `: make a new folder called Linus_hands_on
- `touch my_file.txt` : create a file my_file.txt
- `nano my_file.txt` : Open nano text editor
- `cat my_file.txt` : Display contet of the file in the terminal
- `cp my_file.txt ~/file.txt` : Create a copy of file in the home directory with name file.txt
- `mkdir -p tutorials/RIG` : make a folder tutorials followed by RIG within that folder
- `mv my_file.txt tutorials/RIG/my_file.txt` : move my_file.txt to tutorials/RIG
- `mv my_file.txt linux.txt` : rename my_file.txt to linux.txt
- `cp linux.txt ~/Documents/Linus_hands_on/new.txt` : create a copy of linux to Linus_hands_on with name new
- `rm new.txt` : Remove new.txt (rm can't be used for removing directory (or folder) can be used on for files)
- `rmdir RIG/` : Remove directory RIG (only work with empty directory)
- `rm -r RIG` : Remove directory RIG with content recursively
- `date >> date.txt` : Insert today's date to date.txt (eg Tue May 2022 ....)
- `drwxrwxr-x`: 
- `ls -l` : Shows the permissions of the file (read wite access)
- `ls | grep Documents` : Search for file/folder with Documents 
- `ls | grep '*.pdf'` : find files of type pdf
- `find -name download.png` : find file download.png
- `echo "Hello World"` : Acts like print statement for terminal
- `echo $SHELL` : outputs /bin/bash
- `man mkdir`: shows manual for make directory
- `nano command.sh`: create a .sh file

inside command.sh

```
echo "Hello RIG"
```

- `chmod u+x command.sh` : (add permission )Change permission for to be executable
- `./command.sh` : Execute the contents of the file
- `chmod u-x command.sh` : remove permission of the file

r w x : read wite execute 
4 2 1 : 
(write) : 2 
(read and write) : 4+2 = 6

- `chmod 764 command.sh` : root user read write excute (sum 7) , currecnt user read and write , other user read
- `ps` : Show process id
- `ps -aux | grep arduino` :  Show process id of arduino
- `kill 15187` : Kill arduino process
- `sudo apt install htop` : Install application called htop (can kill process , like task manager in windows)


