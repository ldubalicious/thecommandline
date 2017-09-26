</h1>Intro to Terminal</h1>

Find Terminal App
**command:**    COMMAND-SPACE and search for "Terminal"

Open a New Terminal Window
**command:**    COMMAND-N

Find More Help
**command:**    man [NAME OF COMMAND]
**example:**    man ls

Vim
**definition:** a text editor
**navigating:** j(down) and k(up)
**exit file:**  q

*Note: Always press Enter(Return) to execute command.*

<h1>Navigating Terminal</h1>
<h2>Moving Around Command Line</h2>
For text editing: Left and right arrow keys.
Searching recently used commands in current tab: Up arrow.

**command:**    CTL-A
**definition:** goes to beginning of command line

**command:**    CTL-E
**definition:** goes to end of command line

**command:**    CTL-C
**definition:** keyboard interrupt, creates new line

**command:**    ls
**definition:** list the contents of your current directory

**command:**    ls -l
**definition:** provides full list of information about the current directory, such as total files, names of files, permissions, number of subdirectories, size of file, date of last modification, etc.

**command:**    pwd
**definition:** returns the name of your current directory

**command:**    TAB
**definition:** autocompletes name of directory

<h2>Change Directory</h2>
**definition:** Navigates to a specific directory via the terminal.
**command:**    cd DIRECTORY
**example:**    cd Desktop/

<h1>Managing Files via Terminal</h1>
<h2>Make Directory</h2>
**definition:** Creates a new directory.
**command:**    mkdir NEWDIRECTORY
**example:**    mkdir fieldcore

<h2>Renaming Files</h2>
**command:**    mv
**definition:** renames/moves the file to a new destination
**example _within same directory_:** mv fieldcoretext.txt fieldcoremoved.txt
**example _in directory one level above_:** mv fieldcoretext.txt ../fieldcoremoved.txt

<h2>Copying Files</h2>
**command:**    cp [ORIGINALFILE] [NEWFILE]
**definition:** copies files from one location to another
**example:**    cp fieldcoretext.txt newplace

**command:**    cp -R [ORIGINALDIRECTORY] [NEWDIRECTORY]
**definition:** copies directory and all of its contents
**example:**    cp -R fieldcore newplace

**command:**    scp
**definition:** copies files or folders over a secure, encrypted network
**example:**    scp fieldcore

<h2>Removing Files</h2>
**command:**    rm [FILE]
**definition:** remove files
**example:**    rm fieldcoretext.txt

**command:**    rmdir [NAMEOFDIRECTORY]
**definition:** removes directory
**example:**    rmdir fieldcore

**command:**    rm -r [NAMEOFDIRECTORY]
**definition:** removes directory and all contents
**example:**    rm -r fieldcore

<h2>Creating Text Files</h2>
**command:**    touch [NEWFILE].txt
**definition:** creates a new text file in the current directory
**example:**    touch fieldcoretext.txt

<h2>Using Super User</h2>
**command:**    sudo [COMMAND]
**definition:** forces computer to execute a command as the "super user"
**example:**    sudo rm fieldcoretext.txt

**command:**    sudo !!
**definition:** shortcut to repeat previous command

<h2>Managing Text Files</h2>
**command:**    nano [NEWFILE].txt
**definition:** allows you to edit a text file using Nano
**example:**    nano fieldcoretext.txt

**command:**    CTL-O
**definition:** saves changes to text file

**command:**    CTL-X
**definition:** exits text file

*Note: other commands are listed at the bottom of the Nano file*

**command:**    grep [WORD OR STRING] [FILE].txt
**definition:** searches for word or string of words in a text file
**example:**    grep "home" fieldcoretext.txt
