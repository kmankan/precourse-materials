# TERMINAL

## QUESTIONS

- What are the top 20 commands for mac Command Line Interface (CLI)?
cd : change directory
ls : list what is inside the current directory (-a incl hidden, -l more details, -S sort by size, -C list in columns)
open :  opens a specified file
cp : copy a file to another directory or copy in the same dir
mv : move a file/folder to another directory OR rename a file/folder
touch : create an empty file with whatever specification you want
mkdir : create a new directory (folder)
rmdir : remove a directory
rm : remove a file (-f force)
rm -R : remove an entire directory that may contain other directories/files
sudo : elevate user priviliges while executing a given command
top : list actively running computer processes and utilisation metrics
q : quit/end execution of perpetually running processes (equiv. ctrl c)
clear : clears the terminal screen of all previous commands
ditto : copy all contents of one folder into another folder specified. optional: -V to get verbose output for each file copied.
whatis : one-line description of a command and what is does
man : detailed manual to help understand what a particular command does
exit : close the current terminal session (useful during ssh/remote access)
history -n : see list of all previous commands (!value to bring it up on terminal)n 
cat : prints the contents of a file to the stdout
head : prints the first ten lines of a file
nano : open a specified file in the command line text editor (if no file exists it will create one)
>> : append content to a text file (can be either specified in terminal or copying the content of an existing file)
> : overwrite the contents of a file with specified content (will create new file if it doesn't exist)
pwd : print current directory
chmod : change read, write, execute privileges of a file (three digit number - owner group other permissions - 4 read 2 write 1 execute 0 none; e.g. 700 full for owner, group other none)
echo : print a text value or variable to the terminal. can also print the output of a string literal or variable to a file uisng >> (it will dynamically interpret escape sequences before outputing).
| : 'tee' command, reads stdin and writes to stdout and one or more files



- What is a terminal? A CLI? Why are they synonymous?
A terminal is a program for providing the GUI for text-based interactions with the OS. CLI is a type of interface where users interact with a program or OS by typing commands as text (software implementation vs. style of interaction)

- What is the difference between bash and zsh?
Bash (born again shell) was the shell used on Linux and macOS prior to Catalina. Zsh (Z Shell) was developed as an extended version of Bash with improvements. Become the default shell on macOS after Catalina. Some of its preferred new features include enhanced auto-complete and customization.
A shell is a command-line interpreter that provides a UI for interacting with the OS.
Through the terminal we interact with the shell (e.g. Zsh) 


- What is the difference between Terminal, Console, Shell, and Command Line?
terminal: a program for providing text-based interaction with the OS.
console: originally a physical terminal for system management, in modern times a special interface for sys-level operations and messages.
shell: a command-line interpreter for facilitating user interface with the operation system's service (runs on a terminal)
command line: the line where commands are entered on a CLI.

## RESOURCES

Commands:
https://www.techrepublic.com/article/16-terminal-commands-every-user-should-know/

Bash vs zsh:
https://www.howtogeek.com/68563/htg-explains-what-are-the-differences-between-linux-shells/

What's the difference?
https://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line
