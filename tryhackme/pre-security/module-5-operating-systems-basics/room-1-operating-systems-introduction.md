# Room: Operating Systems: Introduction

**Module:** Module 5 — Operating Systems Basics
**Date completed:** July 10, 2026

## What this room covers

In this room we learn the basics of Operating Systems. An OS is the software that makes it possible for the user to interact with the physical hardware of the computer. Some examples include Windows, Linux, Unix, MacOS and TempleOS

## Key concepts learned

- Operating System (OS) — is a software/program that connects the hardware with the applications or the user it makes sure that the physical hardware is working as intended (Input devices can provide input while Output devices can provide Output ) and secondly it makes sure that the application on the system all work correctly. It acts as a central organizer and it takes control of the CPU and all the other hardware and then distributes it to the application softwares as per their needs
- Kernel Space — This part of the OS has un-restricted access to the hardware and all the system resources. It manages them directly hence it is the locked down part of the OS because any changes to it can disrupt the normal workings of the OS hence only those who are qualified should accesss it
- User Space — This is the part of the OS with which the user interacts it has restricted access to the system resources and applications are deliberately prevented from accessing the hardware directly so anything that a user does in this space ( like play a music video or open a folder ) first has to go to the Kernel space where it asks for permission to access the hardware or the system resources and that too is done by Kernel acting on its behalf

Operating System Duties

- Process Management — Creates, maintains and terminates processses and it decides how much CPU time do each process get and hence makes multitasking seamless
- Memory Management — OS distributes or allocates the memory to the processes and reclaims it when they terminate and if RAM is running low the OS uses Virtual Memory to keep the system stable
- File System Management — Creates, maintains and deletes files and folders and basically managse the process of naming and organizing the files and handles their data
- User Management — Handles Multiple Users and handles how much access does each user have
- Device Management — When a new device is plugged in it loads the drivers ( if present otherwise you have to first install the drivers ) so that the user can easily use the device without any problem

- Graphical User Interface (GUI) — is a type of interface where the user interacts with the system using Graphics like clicking on an icon to open a folder and seeing the files in it. It is less precise but easier to follow and understand especially for non-technical people
- Command Line Interface (CLI) — is a type of interface where the user interacts with the system by typing commands in a terminal ( so no icons or anything just text ). It is much more precise and much less time consuming but the user needs to be much more technical and needs to know the commands

## Tools/commands used

- None

## Something that confused me at first

The Concept of OS itself confused me at first because I have heard the word being used a lot and it is quite fun to know that OS itself is not a sytem rather a software that acts as a system and that it is simply a software that acts as the manager of the computer and manages the way the user, applications and the hardware interact with one another

Secondly the one other thing that confused me was the concept of Virtual memory being used when the RAM is low to keep the sytem stable and the result was very intersting so I will add that in the Intersting section below

## Something that I found to be interesting

So I just learned today that the every computer has some Virtual memory that it uses when the RAM is low ( being used alot ) and this is the concept behind it

So we store all of our programs on our permanent storage devices ( non-volatile ones because otherwise all content will be lost when we shut the computer down ) like SSD's and HDD but we don't directly use the programs from there because they are very slow when compared to RAM ( SSD's are thousands of time slower than RAM while HDD's are even slower ) so we first take that program and put it onto RAM and then use it from there so that everything is fast and seamless but what do we do when the RAM is full or being used to it's limits?

Well then what the computer does is that it makes a decision and whichever program is not being used by the user right now like let's say that the user is using Chrome and VS Code at the same time while Photoshop is open in the background so it will take Photoshop and put it back onto the SSD ( a part of it ) so that the space on RAM is freed and now the user can use it for some other process and when the user opens Photoshop again the computer puts it back onto the RAM and puts the other process that is not being used onto the SSD

Also the CPU doesn't put the whole program onto the SSD rather some small parts of it so even if the user opens the app the small can be retrieved quickly from the SSD ( although the user might have to wait a second or more ) and at the same time some parts of some other application are put onto the SSD

Lastly one question that came to mind right after reading this concept was: What if the user opens like three very heavy apps at the same time and he is not using them one by one rather he has them all opened at the same time and let's say they take more space than the RAM has so what would happen then and the answer came right after that: Either the programs will slow up and feel like they are lagging because some parts of them would go to the SSD or the computer will freeze ( if they are too heavy ) or crash!

## How this connects to real-world security

Operating Systems are the base of any computer or device without them a device can't function properly and they are the most important part and software on the whole computer and they make it possible for the user to interact with the hardware

From a cyber-security point of view since they are the most important part that means that they need the most amount of security as well so that hackers can't enter into them because entering into them or gaining their access would mean getting the access of the whole computer and that is the reason why the OS is divided into the two spaces ( Kernel and User ) so that the most important parts of the OS ( kernel ) can be protected against such threats but different OS allow different amount of access to the Kernel like Windows doesn't allow the user or any program to access the kernel that much ( although i searched it up but they used some advanced terms so i couldn't really understand so this is just my understanding right now and i know that it is quite wrong ) while Linux alllows much more access for the user ( you can even delete it ) and different versions of linux all allow different levels of control and this means that in linux the kernel can be accessed in an easier way hence more chances for it to be hacked but linux must have security as well or else it would have failed by now so it isn't that easy to access the kernel in linux as well but because of the more access a technical user can also make their kernel more secure by adding protections by themselves so in a way it is a double edged sword and I will do some more search on it the next time i encounter this but for now i think that this much is enough

## Next steps / what I want to explore more

I like learning about the fundamentals of computers and right now i would love to continue on the path and go to the next module
