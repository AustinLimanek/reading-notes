# Class 00

[Journal Home](README.md)

Current Readings:

1. [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
2. [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)
3. [More About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)
4. [Manual Pages](https://ryanstutorials.net/linuxtutorial/manual.php)
5. [File Manipulation](https://ryanstutorials.net/linuxtutorial/filemanipulation.php)
6. [Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

## Reading Notes

### The Command Line

I didn't realize that Bash stood for Bourne Again SHell. In addition, I didn't know that Linux what a collection of free software that is used to interact with the operating system. And this could be really any operating system. Furthermore, there seems to be some relationship to the kernel, which is the program in computer memory that facilitates interactions between hardware and software.
Plus, I realized that my current shell in zsh, which is version 5.8.1 (x86_64-apple-darwin21.0).
This, it is clear, I don't have Bash running. However, after a quick google search, it seems that their isn't a big difference between the two shells at my level of use.

### Basic Navigation

I completely forgot from Code 102 that pwd prints the working directory. I have only ever navigated by using `ls` and `.cd`.
This was my first introduction to a long listing format of a file or directory when using the `ls` command in the terminal.
Relative is with respect to the current location of the command line. Absolute path is from the beginning and starts with the `/` character. When thinking about the directory, there is a root, which is the large directory that holds all other directories and files. This is likely a tree like structure. The tree has a root at the root and then the edges are the directories. The files act as leaves. Directories are nodes and files are leaves.
I was unaware that you could hit tab multiple times for a different effect on Tab Completion.

### More About Files

Everything in the Linux system is a file, from the keyboard (read only), to the monitor (write only), to images, and directories. Everything in the operating system is a file. I don't know why this is important, but apparently this is important to understand how the command line interface, the terminal, works.
There are two ways of getting around the space character when searching for files with spaces. You can either use single quotes or you can use the escape character or backslash `\` before the space.
An additional piece of useful information about tab completing is that the space will automatically be escaped. Which saves a lot of time.
Hidden files have a name starting with a full stop or period `.`. The command `ls -a` will show the hidden files. The command line `ls` has a default of not showing hidden files in the terminal.
Finally, microsoft does not have case sensitivity, however, Linux does for files. This is important to remember.

### Manual Pages

Manual pages can be accessed by the command line `man <command line>`. This prints information about the command line that you would like to learn more information about. There is a name, synopsis, and description sections for each manual page command line input. `man -k <search term>` allows you to find a command line that fits ones need. However, if you know the command line that you want but have forgotten a particular argument then you can use `/<search term>` inside the `man <command line>` command line output. If there are multiple hits, the `n` can be used in the `man <command line>` result.

### File Manipulation

`mkdir` is used to make a directory, while `rmdir` is used to remove an existing directory from the existing Linux operating system. `touch [options] <filename>` allows a user to create files when the file name used does not exist in that directory.
`cp [options] <source> <destination>` allows a file to be copied from one location to another.
`rm` like `rmdir` deletes a file. However, `rm` appears to be stronger in the sense that when `-r` is used it deletes all files and directories inside the specified file or directory and removes that file or directory. The option `-i` activates the interactive option which iterates step by step and allows for the abort option to be input.

### Cheat Sheet

This is a summary of all the command lines that were covered in tha above articles included in the Ryan Tutorials. The cheat sheet is organized nicely and is a great resource for future refreshers.

### Things I want to know more about

&copy; 2022, NoMichi
