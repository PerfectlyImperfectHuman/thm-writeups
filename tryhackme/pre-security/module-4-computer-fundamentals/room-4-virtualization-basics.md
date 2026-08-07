# Room: Virtualization Basics

**Module:** Module 4 — Comoputer Fundamentals
**Date completed:** June 29, 2026

## What this room covers

This Room is our introduction to the concept of Virtualization which in simpler terms means dividing a computer into separate computers each with it's own RAM, Storage, OS and Cores allocated to it and it is done by using a software known as a HyperVisor it makes it quite simple to create virtual machines on a computer. This is done so that we can maximize the usage we can get from a computer system

## Key concepts learned

- Virtualization — It is the process of creating one or more virtual computers (Virtual Machines) on a single physical computer using a hypervisor. Each VM has its own virtual CPU(s), RAM, storage, network adapter, and operating system, making it behave like an independent computer.

HyperVisor

- HyperVisor — A HyperVisor is a software that is used to create and manage Virtual Machines on a computer and it allocates RAM, Storage, CPU (cores) and networking to them

- Type 1 HyperVisor — This is a type of hypervisor where the hypervisor runs directly on the hardware instead of on top of a host operating system and each OS on it is like a VM and it loans the RAM and other components according to how we specify them. The main difference between the two types is that in Type 1 you don't have to go through the Computers OS in order to reach the VM you simply have all the VM's created by the HyperVisor which talks directly to the hardware instead as a result of which this type is much faster. The Order goes like this:

Hardware -> HyperVisor (Acts as the Main OS and talks directly with the hardware) -> Different VM's (can include Windows, Linux etc)

- Type 2 HyperVisor — This is a type of hypervisor that runs on top of an OS let's just say that we have Windows 10 installed on our computer and we create a VM and install Kali Linux as the OS on it, then in this type of hypervisor you first need to boot the windows, then reach the desktop and then you start the VM so the order goes:

Hardware -> Windows (Main OS that talks to the hardware) -> HyperVisor (asks the windows or main OS to allocate the RAM and other components ) -> VM (Kali Linux)

- Containers — So when you create VM's using HyperVisor each VM has it's own OS but a container is a type of an isolated environment (It shares the host operating system's kernel instead of having its own kernel.) that is used for specific applications (like a container that is used for only Python it won't have a GUI or any other app on it except for python and the main files for the shared kernel) hence it is much faster than VM's and it is an isolated environment meaning it doesn't interact with any other applications or containers on the main OS. It also doesn't have Virtual RAM or other components allocated to it, it simply uses the components of the main OS but the amount of RAM it can use can be restricted using the container runtime (i.e docker)

## Tools/commands used

- HyperVisor — The concept is defined above

## Something that confused me at first

I had to spend 2+ in order to understand the difference between the two types of hypervisor and containers and even after that I don't fully grasp the concepts but i do think that now I have a little bit clearer image of each in my mind

Type-1: In these the hypervisor interacts directly with the hardware and creates VM's on it and allocates Virtual RAM, Storage, Cores and networking to each of the VM

Type-2: In these the hypervisor lives on top of the main OS and can only be accessed once the main OS is working and it asks the main OS to interact with the hardware for it

I have used this type before, In 2023-2024 I had Windows 10 on my computer and I installed a hypervisor software and created a Virtual Machine on it and then installed Kali Linux on the VM and everytime I wanted to access the VM I would go to the search bar of Windows 10 and search for the hypervisor and start the VM

Containers: This is like dividing the main OS into small apartments which don't interact with one another just the main OS and have specific applications in them

## How this connects to real-world security

Virtualization is a revolutionary topic in my eyes, In the past we needed to have a new physical computer for each different task like if we wanted to host a new website we needed a new computer/server and this was very costly and it consumed a lot of space so to tackle this problem virtualization was invented, now we can have one single super good computer with very good specs and we can create many virtual machines and containers on it and each can perform specific tasks like one can host a website while one can be used for work etc

## Next steps / what I want to explore more

I want to explore this topic more and try and use my computer more efficiently and maximize what i can get from it using virtualization
