# Intro to Terminal

## Finding Your Terminal App <br>
``COMMAND-SPACE`` and search for "Terminal" or whichever Command Line Interface you like to use.

``COMMAND-N `` opens a new Terminal Window

## Finding Manuals for Any Command<br>
`man [NAME OF COMMAND}`, for example:
>man ls

### About Vim
Vim is a basic text editor in which manual files are read.

**To navigate through Vim, use** ``j``(down) and ``k``(up).


**To exit a Vim file, use** ``q``.

**Note:** *Always press ``Enter / Return`` to execute commands in the CLI.*

# Navigating Terminal
## Moving Around the Command Line
**When editing text, use** the ``Left`` and ``right`` arrow keys.


**In order to search recently used commands in current tab, use the** ``Up arrow``.

``CTL-A`` goes to beginning of command line

``CTL-E`` goes to end of command line

``CTL-C`` keyboard interrupt, creates a new line

``ls`` lists the contents of your current directory

``ls -l`` provides full list of information about the current directory, such as total files, names of files, permissions, number of subdirectories, size of file, date of last modification, etc.

``pwd`` returns the name of your current directory

``TAB`` autocompletes name of directory

## Changing Directories
``cd DIRECTORY`` navigates to a specific directory via the terminal, for example:
> cd Desktop/

# Managing Files via Terminal

## Making Directories
``mkdir NEWDIRECTORY`` creates a new directory, for example:
>mkdir fieldcore

## Renaming Files
``mv`` renames/moves the file to a new destination, for example:

>**_within the same directory_** mv fieldcoretext.txt fieldcoremoved.txt

>**_to a directory one level up_** mv fieldcoretext.txt ../fieldcoremoved.txt

## Copying Files
``cp [ORIGINALFILE] [NEWFILE]`` copies files from one location to another, for example:
>cp fieldcoretext.txt newplace


`cp -R [ORIGINALDIRECTORY] [NEWDIRECTORY]` copies a directory and all of its contents, for example:
>cp -R fieldcore newplace


``scp`` copies files or folders over a secure, encrypted network. For example:
> scp fieldcore

## Removing Files
`rm [FILE]` removes files, for example:
>rm fieldcoretext.txt

`rmdir [NAMEOFDIRECTORY]` removes directory, for example:
> rmdir fieldcore

`rm -r [NAMEOFDIRECTORY]` removes directory and all contents, for example:
> rm -r fieldcore

## Using Super User
`sudo [COMMAND]` forces computer to execute a command as the "super user", for example:
> sudo rm fieldcoretext.txt

` sudo !!` shortcut to repeat previous command

## Creating Text Files
`touch [NEWFILE].txt` creates a new text file in the current directory, for example:
>  touch fieldcoretext.txt

## Managing Text Files
`nano [NEWFILE].txt`allows you to edit a text file using Nano, for example:
>nano fieldcoretext.txt

`CTL-O` saves changes to text file

`CTL-X` exits text file

**Note:** *Other available commands are listed at the bottom of the Nano file.*

`grep [WORD OR STRING] [FILE].txt`searches for word or string of words in a text file
> grep "home" fieldcoretext.txt
