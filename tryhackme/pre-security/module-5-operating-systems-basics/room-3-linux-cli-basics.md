# Room: Linux CLI Basics

**Module:** Module 5 — Operating Systems Basics
**Date completed:** July 19, 2026

## What this room covers

This room teaches us the basics of the command-line interface (CLI) in Linux. We acts as a new intern at a cyber-security firm and we learn the basics of the Command Line Interface

## Key concepts learned

- Terminal — is a text-based interface that is used by professionals in order to move around and perform tasks in linux, it is not graphic based so you only type commands and the result is also in the form of text but it is much more quicker (once you become comfortable) and gives much more control hence it is used

## Tools/commands used

- pwd (Print Working Directory) — it is used to print the directory we are currently in for example if we are at /home pwd would print /home it is used when you don't know which directory you are in currently
- ls (List) — it is used to list all the files in a directory just like when on GUI you open a folder and see all the files inside it similarly on linux you type ls to see all the files inside a directory/folder
- ls -l — used to show a detailed list ( with more information )
- ls -a — is used to show all the files in the folder including the hidden files as well
- ls -al — is used to show all the files in a folder including the hidden files and in a detailed list style
- cd (Change Directory) — it is used to change the directory just like in GUI we double click on a folder to go inside it, on linux we simply write cd followed by the directory name and we go inside it and then we can use ls to list all the files and folders in it
- cat — it is used to read a file let's say you have a txt file that you want to read (names.txt) in GUI you would open it by double clicking while in the terminal you simply write cat followed by the name of the file and you can read it right there in the terminal
- whoami — it is a command that tells you who you are logged in as for example let's say you are logged in as User1 so running the command will give you "User1" as the response
- uname — gives you the name of the operating system you are on for example on Linux it would give you "Linux" as the response
- uname -a — is used to give you useful information about the system you are using including the OS, hostname, version, the hardware platform (x86 or x64 or both) and the OS type (for example GNU/Linux)
- df -h (-h stands for human readable) — it is used to see the disk usage or available space on the system
- find (directory where you want to find the file) -name (name of the file) — is used to search for or find a file in a specific directory and if you don't know the directory you simply use "/" to represent the whole system

## Something that confused me at first

I have been using Linux for the past few months (even before I started learning cyber security) so I know most of these basic commands even though I don't use the terminal right now I use the GUI but after this room I will try and use the terminal for the things that i can use it for right now like viewing a file or something like that

The only thing that confused me a little was the flags since I don't really know if they always have the same meaning like when you use -a does it mean that everywhere that you use it with every command it simply shows the hidden files or does the meaning change with the command like with one command it is used to show hidden files while with the other one it is used for an entirely differnet purpose

So I just searched it up and it seems like that the meaning of the flag does depend on the command being used so they don't have a universal meaning and the meaning is dependent upon the command being used so a question popped into my mind right after reading this: Then How does a user know when to use which flag do they need to memorize them all?

The Answer is that you don't have to memorize anything rather you can just use these:

--help flag is used with a command like "ls" to tell you about all the flags that can be used with it and what each flag does
"man" is a command that can be used to get information about any other command like "man cat" (this was funny) to get the information about the cat command and it tells you what the command does and what it is used for and the flags that can be added to it and what each flag does

## How this connects to real-world security

This connects with the real world because linux is one of the most popular Operating Systems in the world and it is used widely by many people and almost all of the people learning cyber-security need to learn linux because it is the base upon which everything else is built upon and for you to learn the CLI of linux you need to learn the basic and most used commands of linux by heart and these commands and this room gave us our first look into the terminal which is the place where we would spend most of our time in

## Next steps / what I want to explore more

I learned some new commands and renewed my knowledge of some of the command I knew and I will try my best to use them daily so that they become send nature to me and I would like to continue my journey and move to the next room and learn some more commands
