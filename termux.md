# ** TERMUX COMMAND**
*Use these some command to use Termux*

> Getting All Updates
apt-get updatw

> Giving Access to File System
termux-setup-storage

> Updating & Upgrading Package
pkg update && pkg upgrade

> Creating/Opening File
nano [file name]
vim [file name]

> Installing Vim Editor:
pkg install vim

> Installing PHP:
pkg install php

> Installing MariaDB:
pkg install mariadb

> Installing Zsh Shell:
pkg install zsh

> Checking The Shell Used:
echo $SHELL

> Switching to Zsh Shell:
chsh -s zsh
echo zsh >> ~/.bashrc

> Configuring Permission Access of File:
chmod [number] [number] [number] [file name]

> Number of Permission Access:
7: rwx
6: rw-
5: r-x
4: r--
3: -wx
2: -w-
1: --x
0: ---

> Checking Web Sever Process:
ps aux | grep php

> Stopping Web Server Process in The Background:
kill [PID]

> Stopping All Web Server Process:
pkill -f "php -S"