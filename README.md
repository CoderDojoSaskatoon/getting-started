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

#### `add`
This command will "stage" the changes you have made to a file. Once the file looks good to share, you can add it with `git add filename`.

#### `commit`
This command will commit all the changes you have staged to your git log. Do this once you are very sure your changes are okay. You also need to add a message for your commit, letting yourself or others know why you made those changes, you can do this with `git commit -m "This is my message!"`

#### `stash`
This command will temporarily remove all of the changes you've made that have not been commited or staged on your branch. This can be useful if you want to `pull` some changes onto your branch. To get your changes back, you can use `git stash pop`.

### Installing Homebrew
Homebrew is a program for Mac that helps you install other applications you can use in your terminal. Before installing something, you might want to check if you have it already. You can usually check this on a Mac by running `which program-name` where "program-name" is the application you want to check. To check if you have Homebrew installed for example, run `which brew`. If you get a response like `/usr/local/bin/brew`, then you know that program is installed. If you get a response like `brew not found` then that program hasn't been installed yet.

To install brew, run the command `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Once you have Homebrew installed, you can check that it works by using the command `brew --version`

### Installing Node
Node is a special application for running JavaScript programs on your computer. You don't need Node in order to write JavaScript code, but Node allows you to write JavaScript that can do special things like run a server or use JavaScript packages easily.

#### Installing Node with Homebrew
This is the preferred way if you have a Mac since it will install Node exactly where you want it to be and manage your updates with `brew update`. To install Node using Homebrew run the command `brew install node`. This installs the application "node" whcih you can use to run your JavaScript programs on your terminal as well as "npm" which helps you install JavaScript pacakges, which is code that other developers have written and shared.

#### Installing Node with the Installer
You can also download an installer from https://nodejs.org/en/download/.
