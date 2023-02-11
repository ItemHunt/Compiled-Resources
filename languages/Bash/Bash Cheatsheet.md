# **Bash Cheatsheet**

## **Introduction**
Bash is a command-line interface language that is regularly used in things like Linux, Git Bash, and others. In this cheatsheet, you can find a list of Bash commands that you can use as well as other useful commands (which may require downloading additional things for them to work). The cheatsheet will also contain a list of learning resources you can refer to if you want to learn or enhance your understanding of Bash.

<!--
test
for future reference
## Contributors
<a href="https://github.com/ItemHunt/Bash-Cheatsheet/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ItemHunt/Bash-Cheatsheet" />
</a>
->
<!-- Contributors section made with [contrib.rocks](https://contrib.rocks). -->


## **Table of Contents**
### **General bash**
- [Essentials](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#essentials)
- [Search & Navigation](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#search--navigation)
- [System Details & Modification](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#system-details--modification)
- [Directory or File Use/Modification/Deletion/Creation](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#directory-or-file-usemodificationdeletioncreation)
- [Networking & Servers](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#networking--servers)
- [Package Management](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#package-management)
- [Process Management](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#process-management)
- [Others](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#others)

### **Git Bash**
- [General Commands](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#general-commands)
- [Git Branches](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#git-branches)
- [User-Setting Modification](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#user-setting-modification)
- [Others](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#others-1)

### **Bash Shortcut Keys and Symbols**
- [Symbols](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#symbols)
- [Bash Shortcuts](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#bash-shortcuts)

### **Additional Information & Learning Resources**
- [Additional Information For Bash](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#learning-resources-list)
- [Learning Resources List](https://github.com/ItemHunt/Compiled-Resources/blob/main/languages/Bash/Bash%20Cheatsheet.md#learning-resources-list)


## **Cheatsheet**
### **General Bash**
#### **Essentials**
- **$ man \<cmd> -** Displays a detailed explanation of the specified command
- **$ \<cmd> --help** Displays a brief explanation of the specified command
- **$ apropos \<keyword> -** Searches for a command that correlates to the specified keyword
- **$ sudo -** Allows you to act as the root user for one command
- **$ clear -** Clears the terminal
- **$ help -** Shows a help menu

#### **Search & Navigation**
- **$ pwd -** Prints current working directory
- **$ ls -** List all items in current working directory
- **$ cd \<direcotory/../-> -** Change working directory, not providing an argument makes you return to your user home directory
- **$ locate -** Uses the locale database to search for things on the system (Note that you may need to install mlocate)
- **$ updatedb -** Updates the locale database for the locate command
- **$ which \<input>-** Provides the path to the specified input
- **$ find \<input>-** Searches for files in a directory hierarchy
- **$ grep \<input>-** Searches for specific results that have given patterns

#### **System Details & Modification**
- **$ whoami -** Tells you what user you are logged in as
- **$ id -** Gives user identity
- **$ hostname -** Tells you the name of the current host system
- **$ uname -** Tells you some basic details about the system
- **$ addgroup -** Adds a group to the system
- **$ delgroup -** Deletes a group from the system
- **$ useradd -** Creates a user
- **$ usermod -** Modifies a user account
- **$ passwd -** Changes the password of a user
- **$ su -** Used to switch users
- **$ lsblk -** Lists block devices
- **$ lsusb -** Lists USB devices
- **$ lsof -** Lists opened files
- **$ lspci -** Lists PCI devices

#### **Directory or File Use/Modification/Deletion/Creation**
- **$ mkdir \<name)> -** Creates a directory inside the current branch of the repository
- **$ rmdir \<name> -** Removes a target directory
- **$ rm \<name> -** Removes a target file/directory
- **$ cat \<name>-** Prints the contents of the file into the terminal
- **$ mv \<input>-** Used to move or rename files
- **$ cp \<input>-** Used to copy files or directories
- **$ touch \<file.ext> -** Allows you to create a file of your choice
- **$ chmod -** Changes the permissions of a file or directory
- **$ chown -** Changes the owner and group of a file or directory

#### **Networking & Servers**
- **$ ifconfig -** Used to deal with the network interface
- **$ ip -** Used to deal with your networking
- **$ netstat -** Shows network status
- **$ curl \<input>-** Utility used to transfer data from or to a server
- **$ wget \<input>-** Can be used instead of 'curl' to get files from FTP or HTTP server
- **$ python3 -m http.server -** Used to start a Python3 web server on TCP port 8000

#### **Package Management**
- **$ dpkg -** Low-level package manager used to install, remove, or configure Debian-based packages
- **$ apt -** High-level package manager
- **$ aptitude -** Another high-level package manager that can be used as an alternative to apt
- **$ pacman -** Package manager for Arch Linux or Arch-based systems
- **$ yay -** Package manager for accessing the Arch User Respository (AUR)
- **$ snap -** Used to install, remove, and configure snap packages 
- **$ flatpak -** Used to install, remove, and configure flatpak packages
- **$ gem -** Standard package manager for Ruby
- **$ pip -** Standard package manager for Python

#### **Process Management**
- **$ systemctl -** Used to manage processes and daemons
- **$ ps -** Outputs current processes
- **$ journalctl -** Shows process journal
- **$ kill -** Used to send a kill signal to a process
- **$ bg -** Puts a process into background
- **$ jobs -** Outputs a list of all processes running in the background
- **$ fg -** Places a process into the foreground

#### **Others**
- **$ ss -** Used to investigate sockets
- **$ who -** Shows who is currently logged in
- **$ env -** Prints the environtment or sets and then runs a commands
- **$ tree -** Command to list the things inside of a directory recursively
- **$ nano -** Used to open and use Nano, a terminal based text editor that is easier to use than Vim
- **$ vim -** Used to open and use Vim, a terminal based text editor that can do a lot of stuff but is difficult to use
- **$ nvim -** Used to open and use NeoVim, the upgraded version of Vim
- **$ more -** Pager used to read STDOUT or files
- **$ less -** Upgraded version of the more command
- **$ head -** Prints the first ten lines of STDOUT or a file
- **$ tail -** Prints the last ten lines of STDOUT or a file
- **$ sort -** Sorts the contents of a file or STDOUT
- **$ cut -** Removes sections from each line of files
- **$ tr -** Replaces certain characters
- **$ column -** Utility that format its input into multiple columns
- **$ awk -** Pattern scanning and processing language
- **$ sed -** A stream editor for the transformation and filtering of text
- **$ wc -** Prints newline, word, and byte counts for a provided input

### **Git Bash**
#### **General Commands**
- **$ git -** Version control system utility
- **$ git status -** Shows you the status of your Git repository (what is staged, unstaged, new, and what was modified recently)
- **$ git add \<input> -** stages file/s
- **$ git init -** Initializes or activates or converts the current working directory into a git repository
- **$ git commit -m \<insert commit comment> -** Shortcut for committing files/changes and adding a comment without going into your text editor (e.g. Vim, Nano)
- **$ git push -u origin -** Pushes all contents of the master branch into the remote repository your local repository is connected to. This allows your remote repository files to be updated or to increase/decrease in number
- **$ git pull -** Pulls all files/changes made on the remote repository into your local repository
- **$ git remote add origin \<insert remote repo link> -** Allows you to connect your local repository into a remote repository (or online repository)

#### **Git Branches**
- **$ git branch \<branch name> -** Helps you create a new independent branch on your local repository
- **$ git merge \<branch name> -** Allows you to merge a branch into the master branch
- **$ git checkout \<branch name> -** Switches your git repository branch to the specified branch

#### **User Setting Modification**
- **$ git config –global core.editor \<insert editor you want eg. vim, nano, etc> -** Helps you change your text editor
- **$ git rm –cached \<name of file with format> -** Unstages a specified file
- **$ git config –global user.email \<insert your email> -** Allows you to set your Git email
- **$ git config –global user.name \<insert username> -** Allows you to set your Git name

#### **Others**
- **$ git clone \<link of git repo> -** Allows you to clone an existing repository into your system
- **$ git remote -** Shows you if your local repository is connected to a remote repository (or online repository)
- **$ ssh-keygen -t rsa -C \<insert your Github Email> -** Allows you to generate a ssh key that you can connect to your github. This allows you to have a secure way of interacting with your remote repository using your local repository
- **$ git log -** Shows you all previous saved changes


### **Bash Shortcut Keys and Symbols**
#### **Symbols**
- **&& -** Stands for 'and' in programming. You can use this to trigger multiple different commands in the same time
- **|| -** Stands for 'or' in programming. You can use this to trigger commands based off conditions. For example, if the first command does not work, the second will run instead

#### **Bash Shortcuts**
- **arrow up/down** Key on the bash terminal allows you to check and navigate previously used commands
- **ctrl + l** When in the bash terminal is the shortcut way to clearing your terminal screen
- **q** When in the bash terminal allows you to exit whatever your stuck to (like a log or something) and return to the position where you can execute commands
- **ctrl + a** Moves your cursor to the beginning of the line
- **ctrl + e** Moves the cursor to the end of the line
- **ctrl + <- or ->** Lets you move quickly in either the left or right direction, useful if you typed something long and you want to fix something in-between
- **alt + b or f** Allows you to jump backward or forward
- **tab** Initiates auto complete
- **ctrl y** Allows you to paste the erased text or word
- **ctrl + c** Allows you to end the current task or process by sending a SIGINT
- **ctrl + z** Converts a current process into a background one via SIGTSTP signal
- **ctrl + r** Lets you check command history
- **alt and tab** Helps you switch between opened applications
- **ctrl +** Lets you zoom in
- **ctrl -** Lets you zoom out
- **ctrl + u -** Erases everything from the current spot of the cursor to the beginning of the line
- **ctrl + k -** Erases everything from the current spot of the cursor to the end of the line
- **ctrl + w -** Erases the word preceding the cursor position
- **ctrl + d -** Closes STDIN pipe, also known as End-Of-File (EOF) or End-of-Transmission
- **ctrl + z -** Closes the current process by sending a SIGTSTP signal
- **Alt + Tab -** Switch between opened applications

## **Additional Information For Bash**
- **.bashrc -** There is this dot file called .bashrc in the user home directory which you can use to create aliases which works like keywords to help trigger a specific command/set of commands

### **Additional Information for Git Bash**
- **.gitignore -** Is a file that allows you to have Git ignore specific files or folders in your local repository. To use it, simply put the file name or folder that you want to be ignored. If you have a text file called "Text.txt" just type its name inside .gitignore to have Git ignore that specific file

## **Learning Resources**
### **Bash**
- Linux Fundamentals (video) https://www.youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL
- HTB Academy Linux Fundamentals (website) https://academy.hackthebox.com/module/details/18

### **Git Bash**
- Git Documentation Link (website) https://git-scm.com/doc
- GitHub Documentation Link (website) https://docs.github.com/en
- Easy To Understand Beginner Guide to Git (video) https://www.youtube.com/watch?v=SWYqp7iY_Tc
- Git Crash Course (video) https://www.youtube.com/watch?v=RGOj5yH7evk&t

