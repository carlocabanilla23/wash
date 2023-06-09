Washinton Shell
Washinton Shell is a simple command line interpreter or shell that reads and executes commands from users. It is written in C and supports a variety of built-in and external commands.

Getting Started
Clone the repository to your local machine to get started.

bash
Copy code
gcc -o wash wash.c
This will create an executable named wash.

Usage
To start the shell, run:

bash
Copy code
./wash
You will be greeted with a prompt like:

bash
Copy code
wash>
You can now start entering commands.

Commands
Washinton Shell supports a number of built-in commands:

cd <dir>: Change the current directory to <dir>.
pwd: Print the current directory.
setpath <dir>: Set the PATH environment variable to <dir>.
clear: Clear the shell screen.
help: Display help information.
exit: Exit the shell.
The shell also supports external commands, including:

ls: List directory contents.
date: Print or set the system date and time.
ps: Report a snapshot of the current processes.
df: Report file system disk space usage.
lsblk: List block devices.
./new_head: A custom program to display the first N lines of a file (like the UNIX head command).
You can redirect the output of commands to a file using >:

bash
Copy code
wash> ls > out.txt
You can also take input from a file for commands using <:

bash
Copy code
wash> ./new_head -n 5 < file.txt
Contributing
Contributions are welcome. Please open an issue to discuss the proposed change or submit a pull request.

License
This project is open source and available under the MIT License.

