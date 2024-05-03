Developers of kali linux create it is a replacement for the earlier backtrack distribution.

Backtrack was a powerful platform that provides the tools or successful  Peneteration testing.

Based on Knoppix linux
Knoppix is an o.s based on debian design to run directly from cd/dvd or a usb flash drive 

Debian is an open source o.s that uses linux kernel.

Kali linuxs is  Reramp version of backtrack

In 2013 kali linux 1.0 was released
The most advanced, robvbust and stable peneteration testing distributions.

It was developed by Matiahanoni and dovean kearns of offensive security.

A linux distributions is an operating system mode from software collection that is based upon linux kernel.

# Linux fundamentals

Kernel is a computer program at the core of a computer operating system with complete control over everything in the system.

It faciliates interaction or interface between hardware and software components.

The kernel take responsibility for deciding at any time which at the many running programs should be allocated to the processors.

Ram is used to store both programs instruction and data. the kernel is responsible for deciding which memory each process can use.

It handles peripheral slike keyboards, monitors printer and speaker.

# Types of kernel

1.] Mono lethic kernel
2.] Micro kernel
3.] Hybrid kernel

![[Monolithic-Architecture.png]]


![[microkernel-in-operating-system 1.png]]



![[Hybrid-Kernel-Architecture-23.png]]

# Shell

The shell and kernel are the part of this operating system.

When a user gives his command for performing any operation. then the request will goes to the shell ports.

The shell parts is also called as the interpreter which translate the human program into the machine learning language.


Then The request will be transferred to the kernel.
A Shell provide you with an interface to the linux system.

Shell is an environment in which we can run our commands, programs and shell scripts.

# Types of shell

# Bash  shell (bourne again shell)

- Developed for the GNU project
- The actual standard linux shell
- The $ character is the default prompt.

# Borne Shell

- Orignal Unix shell written by bill joy at UC berkely.
- First shell to appear on Unix system.
- Usually installed as /bin/sh on most versions of Unix.
-
# Shell Csh

- The % character is the default prompt.
- idea for learner comfortable with C
- mostly network admin use the shell.

# Linux file system hierarchy

The file system hierarchy standard (FHS) project was began in 1993.

The goals was to come to consensus on how directories should be organized and which file should stored where.

So that distributions could have a single reference point from which to work.

# (FSH)

/Root
-  /bin
- /boot
- /dev
- /etc
- /home
- /lib
- /opt
- /root
- /sbin
- /src
- /tmp
- /usr
- /media
- /var
- /mnt

# /bin

Contains commands that may be used by both the system administrator and users.

# /boot

This directory contains everything required for the boot process.

/boot stores data that is used before the kernel begins executing user-mode programs.

The operating system kernel must be located in either /or /boot

# /dev
The /dev directory is the location of special for device files.

All hardware files are present in /dev devices folder.

# /etc

The /etc hierarchy contains configurations files.
Configuration files for boot loaders that are not required at boot times must be placed in /etc Ex:- user passwords, group, users.

# /home

user home directories  -> standard users.

# /lib

The /lib directory contains those shard library image needed to boot the system and run the commands in the root file system.

Ex:- When you are running a command or running a program the files required for its execution and proper execution are present in the lib.

# /media

Mount point for removable media

Ex:- if any pen drive or storage device is installed or any extra removable device is installed  it remains in the media folder.

# /Mnt

This directory is provided so that the system administrator may temporarily mount a file system as needed.

Ex:- in the main folder we can mount temporary files and the administrator manage these files system.

# /opt

Add an application software packages

Ex:- if you have installed some third party applications one software , then their files are in opt.

# /root

Home directory for the root users.

# /sbin

Utilities used for system administration 
/sbin contains binary essentials for booting, restoring recovering, and /or reparing the system in addition to the binaries in /bin.

Ex:- sbin certain those files which the administrator can run if you see any problem while booting to make changes in the booting files, to restore the system and to recover it, it remains to repair the system in /sbin.

# /srv

/srv contains site-specific data whcih is served by this system.

If you were using the Apache http server to serve a website, you'd likely store you r website is file in a directory inside the/srv directory.

Ex:- service related data is available, we have configured apache server, people will be access data from ftp server. where the files of ftp server be found in /srv.

# /tmp

The /tmp directory must be made available for programs that require temporary files.

Files and directories located in /tmp be deleted whenever the system is booted.

Temp files are available to programs and are automatically deleted when the system boots.

# /usr

/usr is shareable read-only data the /usr directory contains applications and files used by users.

# /var

/var contains variable data files

This include files, administrative and logging data, and temporary files.

Explain:- /var is still a directory for variable data used by the system. think of it is a folder that holds information program use and change often.

logs:- keep track of what's happening on the system.
spool data:- hold things wasting to be processed, like print jobs.
cache:- store temporary data to speed things up 
database files:- data for some programs.

# /proc

It contain special files that represent system and process information.

Example:- /proc is a special file system that act like a window into the running systems.
it doesn't store actual files, but rather provide real time information about.


running processes each processes has a subdirectory
system hardware
memory usage
kernel configuration

Think of it's a control and information centre for the kernel. letting you see what's going on under the hood.

# /lost  + found/

This is an important directory which is useful for recovering files which are not properly close due to many reasons such as power failure.

Explain:- /lost + found directory is a special place used to store fragments of files recovering from a crash or filesystem errors. it's like a lost and found for corrupted data.


# /run 
This directory contains system information data describing the system since it was boored.

Explain:- /run directory in kali linux is temporary storage location for a system processes. Think of its a workspace that get cleared out when you reboot it hold things like.

process ID's PIDS :- files contains unique identifier for running programs.

device files:- temporary files representing corrected devices.

mount point:- information about currently mounted drivers and file system.

It's essentially in area for ongoing system operation and it's contains are not meant to be persistent.

# linux file types

When navigation the linux file system you are sure to encounter different file types.

There are different file types within the linux program system.

- -: regular file
- d: directory
- c: character device file
- b: blocked device file 
- s: local socket file
- p: named pipe 
- l: symbolic link

# Regular files

Most common file type found on the linux system you can create regular file with touch command.

# Directory files

Directory is second most common file type found in linux. directory can be created with the mkdir.

# character and block device files

character and block device files allow users and programs to communicate with hardware peripheral devices.

# local socket file

local domain socket are used for communication between processes generally, they are used by services such as x windows. spylog and etc.

In kali linux c and other linux systems, local socket file provide a mechanism for processes on the same machine to communicate with each other efficiently. unlike network socket that use TCP/IP model for communication across a network , local sockets faciliate inter-process communication (IPC) within the system itself.

# key characteristics

file based:- local sockets exist as regular files with the sock extension in the file system, typically located in the directories like /var/run or  /tmp.

Bidirectional:- they enable two way data exchange between processes.

Lightweight:- compared to network sockets, local sockets offer faster and more resource-efficient communication due to the absence of network ovverhead.

Example scenario:- Imagine you have a web server (like apache) running in kali linux. It might use a socket file (e.g) /var/run/apache2.sock) to allow web applications (like php scripts) to correct and exchange communication within the system itself, improving performance.

# common uses

Database servers:- mysql, postgresql  and other database server often use local sockets for client connection.

Windows system:- x window system (x11) leverages local sockets for communication between the x server and client application.

wshom applications:- developers can create programs that utilize local sockets for tailored IPC needs within their software.


# Accessing local sockets file

process listing:- tools like ==lsof== or ==netstat== can display information about open sockets including local socket file. for example lsof+g /var/run/apache2.sock would show processes connected to the apache sockets.

permissions:- local sockets have ownership and permission settings that control which users or processes can access them.


Remember that local socket file are not intended for communications across networks. they are specifically designed for efficient inter-process communication within a single system.

# Named pipe

Named pipe allows communication between two local processes. they can be created by the mknod command and removed with the rm command.

here's what a named pipe also called FIFO is in kali linux.

# inter process communication

It's a special files that allow programs to exchange data.

# like a pipe, but with a name

unlike regular pipes, named pipes exist in the filesystem within a name, so multiple programs can access them.

# first in first out (FIFO
data goes first, come out first.

# created with mkfifo
use this command to create a name pipe.

# symbolic link

with symbolic link an administrator can assign a file or directory multiple identifies

Imagine a symbolic link in kali linux like a shortcut on you computer. instead of copying a whole life. this way you can access the file from the shortcut just as easily . but you save space by not having duplicates.

Here's what make symbolic link ready.

Easy access:- they provide quick access to files or folder in different location without moving the orignals.

Save spaces:- no duplicate files means less storage used.

Flexibility:- they can point to files anywhere on your system, even on different drives.

Think of it like having a fancy bookmark that takes you right to the page you  want in a book, no matter where you open the book.

# Control operators

with the help of control operators you can put more than one command in the command line. it helps in performing function.

# ; semicolon

# ampersand &

When a line and with an ampersand & the shell will not wait for the command to finish.

you will get your shell prompt back and the command is executed in background. you will get a message when the command has finished executing in background.


# double ampersand &&

The shell will interpret && as a logical AND. when using second command is executed only if the first one succeed. (return as zero exit status)


# panel sign '#'

Everything written after a pound sign (#) is ignored by the shell. This is useful to write a shell comment, but has no influence on the command execution or shell expansion.

# I/O redirection

This features of the command like enables you to redirect the input and/or input of commands from and/or to files.

# >> append "it is cold today" >> simple.txt

# Filter and pipes

When a program takes its input from another program it performs some operation on that input and writes the result to the standard input. it is referred to as its filter.


# Grep command

The Grep command Searches a file for lines that have a certain pattern. The syntax is $ grep pattern file (s)

The name "grep" cores from the (a unix line editor) command  g/r/e/p which means "Globally search for regular expressions and print all lines conttaining it".

# Pipe command

more than two commands may be linked up to a pipe. "|"

# Process management

Whenever you issue a command in unix, it creates or starts , a new process. When you tired out this is command to list the directory contents, you started a process. is an instance of a running program.


# starting a process

when you start a process (run a commands), there are two ways you can run it

Foreground process

Background process

In kali linux, just like any other computer system, process management is all about juggling the programs that are running. Imagine you have bunch of cook in a kitchen (The programs), all working on different dishes (tasks). 

Process management helps you see who doing what:- you can check which programs are running and what resources they're using memory. with commands like PS and TOP.

# Take control

You can start, stop , or prioritize programs. need a program to focus on it tasks, you can adjust its priority. is a program running slowly? you can stop it to free up resources for others.


# Foreground services

Needs your attention and stays active even when you leave the app.

# Background services

Works silently in the background without needing your immediate attention.

# Scripting introduction

A shell script is a computer program designed to be run by the unix/shell. It is a file that contains ASCII text data files, text files, data sets.

Absolutely! scripting in kali linux is like putting together a recipe for your computer instead of typing out commands one by one. you write them down in a step list. this let you automate repetitive task, like checking security vulnerabilities on multiple machine.

**Ingredients (commands)**:- you use the command you already know from kali linux.

**Recipe  (scripts)**:- you write these commands in a text file, like a grocery list.

**Cook book (shell)** :- kali linux use a program called  a "shell" to follow your recipe.

**Cooking (running)**:- When you run the script the shell follows your instruction automating the task.
# Note

This saves you time and effort, especially when you need to do same things over and over.


# Root system

This is also call ed superuser and would have complete and untattered control of the system. A Superstar can run any command without any restriction. 

This user should be assured as a system administrator.

# service accounts

Service account are created by installation packages when they are installed. these accounts are used by services to run processes and execute functions. These account are not used in routine work.

# user account

user account provide interactive access to the system for users and group of users.

linux support a concept of group account which logically groups a number of accounts. every account would be a part of another group account. 

A linux group play important role in handling file permission and process management.


# Managing user and groups.

There are four main user administration files.

# /etc/passwd

keep the user account and password information the files hold the majority of information about acccounts on the unix system.

# /etc/shadow

holds the encrypted password of the corresponding account not all the system support this file.

# /etc/group

This file contain the group information for each account

# /etc/gshadow

This file contain secure group account information


# Managing user and groups

 - **user add** :- adds account to the system.
- **user mod**:- modifies account attributes
- **userdel**:- delete account from the system
- **group add** :- modifies group attributes
- **groupdel**:- remove group from the system
 

# Short notes

**Linux Fundamentals**

- **Kernel:** Core program controlling the system, managing hardware and software resources.
- **RAM (Random Access Memory):** Stores program instructions and data for temporary use.
- **Shell:** Interface for users to interact with the system using commands.
    - **Types:** Bash (most common), Bourne Shell, Csh

**Linux File System Hierarchy**

- **FHS (File System Hierarchy Standard):** Defines directory structure and file placement for consistency across distributions.
- **Common Directories:**
    - **/bin:** Essential commands for all users (e.g., cat, ls, cp).
    - **/boot:** Files required for the boot process (e.g., kernel).
    - **/dev:** Device files representing hardware devices.
    - **/etc:** System-wide configuration files.
    - **/home:** User home directories containing personal files and settings.
    - **/lib:** Shared libraries needed by programs in **/bin** and **/sbin**.
    - **/media:** Mount point for removable media (e.g., USB drives).
    - **/mnt:** Temporary mount point for file systems.
    - **/opt:** Optional application software packages.
    - **/root:** Home directory for the root user.
    - **/sbin:** System administration utilities.
    - **/srv:** Site-specific data served by the system (e.g., website files).
    - **/tmp:** Temporary files, deleted on reboot.
    - **/usr:** Read-only shareable data, containing applications and user files.
    - **/var:** Variable data files (e.g., logs, spool data, cache).
    - **/proc:** Special file system providing information about running processes.
    - **/lost+found:** Recovers file fragments from crashes or errors.
    - **/run:** Temporary storage for system processes (e.g., PIDs, device files).

**Linux File Types**

- **Regular File:** Most common type (e.g., text files, documents).
- **Directory:** Contains other files and subdirectories.
- **Special Files:** Represent hardware devices (character, block).
- **Sockets:** Facilitate communication between processes.
- **Named Pipes (FIFOs):** Allow data exchange between two processes.
- **Symbolic Links:** Shortcuts to files or directories elsewhere.

**Control Operators**

- **Semicolon (;):** Execute multiple commands sequentially.
- **Ampersand (&):** Run a command in the background.
- **Double Ampersand (&&):** Execute the second command only if the first succeeds.
- **Hash (#):** Comment line, ignored by the shell.

**I/O Redirection**

- Redirects input or output of commands to/from files (e.g., >> to append).

**Filters and Pipes**

- **Filters:** Process data from another program (e.g., grep).
- **Pipes (|):** Send output of one command as input to another.

**Process Management**

- **Processes:** Instances of running programs.
- **Foreground Processes:** Run in the terminal and require your attention.
- **Background Processes:** Run silently in the background.
- **Commands:** ps (list processes), top (monitor process activity).

**Scripting**

- **Shell Scripts:** Automate repetitive tasks using a series of commands.

**User Accounts and Groups**

- **Root:** Superuser with unrestricted access to the system.
- **Service Accounts:** Used by services to run processes.
- **User Accounts:** Provide access to the system for individual users or groups.
- **Groups:** Logically group accounts for permission management.

**Managing Users and Groups**

- **Commands:**
    - useradd: Add a user account.
    - usermod: Modify user attributes.
    - userdel: Delete a user account.
    - groupadd: Add a group.
    - groupmod: Modify group attributes.
    - groupdel: Delete a group.

**Additional Notes**

- **/etc/passwd:** Stores user account information (excluding passwords).
- **/etc/shadow:** Stores encrypted user passwords (on systems that support it).
- **/etc/group:** Contains group information for each account.
- **/etc/gshadow:** Stores secure group account information (on systems that support it).

This revised version condenses the information while maintaining clarity. I hope it's helpful!







