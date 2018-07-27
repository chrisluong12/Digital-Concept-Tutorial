#**Virtual Machines and how to set up a linux virtual machine up on your Mac**
## by Christopher Luong
---

##**Tutorial purpose**
This tutorial explains the abilities of virtual machines and how to install Ubuntu on your mac.
This tutorial is geared toward to people who are new to virtual machines and are interested in its capabilities.

##**What is a virtual machine?**
![image](https://d2gg9evh47fn9z.cloudfront.net/800px_COLOURBOX2286335.jpg)

Virtual Machines (VM) are incredibly important for the developers of today. They allow you to emulate an entire system within your host OS which will
allow you to do many things. Before the existence of Virtual Machines, developers had to buy multiple pieces of hardware that could cost thousands of dollars that
a single laptop could do now.

Virtual Machines are managed by virtualization software. VMware is the post popular and will be used as an example for this tutorial.
They can be run directly on hardware, or alongside a host OS

##**Types of Virtualization**

###Full Virtualization
This is the most common type. It is a full isolation from the host system.
The privileged instructions on the VM passed through the virtual machine manager for translation.
Non-privileged instructions communicate directly with hardware.

##**Paravirtualization**
Similar to full virtualization, but requires modification of guest operating system (OS). A virtual machine is a guest OS when it is run alongside the host OS.
In certain situations, it can have better performance over full virtualization. But, it can have significantly worse compatibility and portabililty.

##**Hardware Assisted Virtualization**
Similar to full virtualization, but supported at the hardware architecture level. This means that the hardware facilitates building a virtual machines and allows the virtual machine to run in isolation.

##How to install Ubuntu
1.Open VMwareFusion
2.Click “File”, “New...”,select “Install from disc or image”, then click “Continue”
3.Click “Use another disc or disc image...” and browse to your ISO file, click “Open”, then click “Continue”
4.Ensure that the “Use Easy Install” box is checked, fill in the required info, then click “Continue”
  *Set your display name
  *Set your account name
  *Set your desired password

5.Click “Customize Settings”
6.Save the virtual machine as whatever your desire







**bold text**

*italicized text*

~~Strikethrough text~~
---
###horizontal rule ^^
---
