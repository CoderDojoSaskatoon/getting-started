# Getting Started
A guide to help you download and install programming applications

## Using a Terminal Program

### For Mac Computers
All Mac computer come with a terminal program installed on them. To find it go to Applications -> Utilities and select the "Terminal" application. This application is very basic but don't be fooled, you can do so much with it! Let's become more familiar with some terminal commands.

## Terminal Commands
To use a ccommand in the terminal, just type it in and hit "enter". Some commands will need arguments which you put in after your command with a space. Some will use special flags to change the command a little bit, you put those in after your command with a space and "-".

### For Mac Computers
`pwd` (print working directory) - this command will show where you are in your file structure. When you first start your terminal program you start in a special place called "root".

`cd` (change directory) - this command will let you change where you are in your file structure. To move into a folder try a command like `cd folder-name` where "folder-name" is the name of a folder. If you ever want to go back to a parent folder, you can use `cd ..` and if you ever want to go all the way back to your root directory, use `cd ~`

`ls` (list) - this command will list everything (folders and filers) in your current directory.

`mkdir` (make directory) - this command will make a new folder with the name you give it ex. `mkdir new-folder` will create an empty folder called "new-folder". It's nice to create a project folder on your root directory where you can save your projects.

## Using `git`
Git is a special program that helps you save changes you make to your code and share them easily with others.

### `git` commands
#### `clone`
This will copy a repository from github.com to your computer. If you want to copy this repository, use your terminal and navigate to your project folder. Then use the command `git clone https://github.com/CoderDojoSaskatoon/getting-started`.

Be careful, if you already have a folder named "getting-started" in your project folder you will get an error.

### Installing Homebrew
Homebrew is a program that helps you install other applications you can use in your terminal. Before installing something, you might want to check if you have it already. You can usually check this on a Mac by running `which program-name` where "program-name" is the application you want to check. To check if you have Homebrew installed for example, run `which brew`. If you get a response like `/usr/local/bin/brew`, then you know that program is installed. If you get a response like `brew not found` then that program hasn't been installed yet.

To install brew, run the command `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
