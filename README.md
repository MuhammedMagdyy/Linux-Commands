# Linux Commands

I've created this repository to help my friends in operating system course at october 6 university.
Here're 2 playlists I've recorded to [How to install debian](https://www.youtube.com/playlist?list=PLs3AnacXmIa_FeAQDF3u2Bf1cY-ZCa_P7) and [it's commands](https://www.youtube.com/playlist?list=PLs3AnacXmIa9qrhcJmxS29VB0zfSkgDPO)

---
## General Commands

| Command | Description |
| --- | --- |
| `date` | shows the current date |
| `cal [month]  [year]` | shows the current calender with selected month and year |
| `clear` | clear all things in terminal |
| `history` | show all history commands |
| `history -c` | deletes all history commands |
| `whoami` | shows the current online user |
| `who` | shows how many times your device opened |
| `echo` | prints a string in the terminal |
| `pwd` | shows where is your current directory |
| `cd [Directory]` | change your current directory to the choosen one |
| `cd -` | change your cuurent directory to the previous one |
| `cd ..` | make a previous step in the directory structure |
| `ls [Directory]` | list all things in this directory |
| `man [command]` | display any command in details |
| `passwd` | change your current password |
---

##  Add / Delete Users 
| Command | Description |
| --- | --- |
| `su` | go to the root and switch the user |
| `exit` | logout from the current user |
| `adduser [user]` | add new user to the system |
| `deluser --remove-home [user]` | delete the user |
--- 

## Create / Delete Files and Directories
| Command | Description |
| --- | --- |
| `cat [Directory / File]` | shows the content of the files |
| `cat > [Directory / File]` | create a new file |
| `mkdir [Directory / Folder]` | create a new folder |
| `rmdir [Directory / Folder]` | delete folders |
| `rm [Directory / File]` | delete files |
| `rm -r [[Directory / Folder]` | Delete all content in the folder |
| `rm -r -i [[Directory / Folder]` | ask after deleting |
---

## Operations on Files and Directories
* cp [-flag] [items] [destination] 
* mv [-flag] [items] [destination] 
<br />

| Command | Description |
| --- | --- |
| `cp [File or Directory] [File or Directory]` | copy the content of the first one to the destination |
| `cp [File 1] [File 2] [Directory]` | copy the files to the choosen directory |
| `cp -r [Directory 1] [Directory 2]` | copy directory 1 to directory 2 |
| `mv [File or Directory] [File or Directory]` | move the content of the first one to the destination |
| `mv [File 1] [File 2] [Directory]` | move the files to the choosen directory |
| `mv [Directory 1] [Directory 2]` | move directory 1 to directory 2 |
| `mv [File / Directory] [new name]` | rename files or directories |
| `mv -i [File / Directory] [new override]` | ask me to override if the name that taken is currently in use |
