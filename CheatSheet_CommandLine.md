# Intro to Terminal

### Find Terminal App <br>
``COMMAND-SPACE`` and search for "Terminal"

``COMMAND-N `` Opens a New Terminal Window


Find More Help (Manual)<br>
`man [NAME OF COMMAND}`
>man ls


Vim : a text editor

**navigating:** ``j``(down) and ``k``(up) |
**exit file:**  ``q``

*Note: Always press Enter(Return) to execute command.*

# Navigating Terminal
### Moving Around Command Line
For text editing: ``Left`` and ``right`` arrow keys.
Searching recently used commands in current tab: ``Up arrow``.

``CTL-A`` goes to beginning of command line

``CTL-E`` goes to end of command line

``CTL-C`` keyboard interrupt, creates new line

``ls`` list the contents of your current directory

``ls -l`` provides full list of information about the current directory, such as total files, names of files, permissions, number of subdirectories, size of file, date of last modification, etc.

``pwd`` returns the name of your current directory


``TAB`` autocompletes name of directory

## Change Directory
``cd DIRECTORY`` Navigates to a specific directory via the terminal.
> cd Desktop/

# Managing Files via Terminal

### Make Directory
``mkdir NEWDIRECTORY`` Creates a new directory.
>mkdir fieldcore

### Renaming Files
``mv`` renames/moves the file to a new destination

>same directory: mv fieldcoretext.txt fieldcoremoved.txt

>one level up: mv fieldcoretext.txt ../fieldcoremoved.txt

# Copying Files
``cp [ORIGINALFILE] [NEWFILE]`` copies files from one location to another
>cp fieldcoretext.txt newplace


`cp -R [ORIGINALDIRECTORY] [NEWDIRECTORY]` copies directory and all of its contents
>cp -R fieldcore newplace


``scp`` copies files or folders over a secure, encrypted network
> scp fieldcore

### Removing Files
`rm [FILE]` remove files
>rm fieldcoretext.txt

`rmdir [NAMEOFDIRECTORY]` removes directory
> rmdir fieldcore

`rm -r [NAMEOFDIRECTORY]` removes directory and all contents
> rm -r fieldcore

### Creating Text Files
`touch [NEWFILE].txt` creates a new text file in the current directory
>  touch fieldcoretext.txt

###Using Super User
`sudo [COMMAND]` forces computer to execute a command as the "super user"
> sudo rm fieldcoretext.txt

` sudo !!` shortcut to repeat previous command

###Managing Text Files
`nano [NEWFILE].txt`allows you to edit a text file using Nano
>nano fieldcoretext.txt

`CTL-O` saves changes to text file

`CTL-X` exits text file

*Note: other commands are listed at the bottom of the Nano file*

`grep [WORD OR STRING] [FILE].txt`searches for word or string of words in a text file
> grep "home" fieldcoretext.txt
