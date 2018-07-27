# **Installing the Linux OS on your Mac**
## by Christopher Luong
---

Go back to the [home page](/README.md/).

## **What is a virtual machine?**
![image](https://cdn1.macworld.co.uk/cmsdata/features/3637265/how_to_install_linux_on_mac_thumb800.jpg)

Virtual Machines (VM) are incredibly important for the developers of today. They allow you to emulate an entire system within your host OS which will
allow you to do many things. Before the existence of Virtual Machines, developers had to buy multiple pieces of hardware that could cost thousands of dollars that
a single laptop could do now.

Virtual Machines are managed by virtualization software. VMware is the post popular and will be used as an example for this tutorial.
They can be run directly on hardware, or alongside a host OS

## **Types of Virtualization**

### Full Virtualization
This is the most common type. It is a full isolation from the host system.
The privileged instructions on the VM passed through the virtual machine manager for translation.
Non-privileged instructions communicate directly with hardware.

### **Paravirtualization**
Similar to full virtualization, but requires modification of guest operating system (OS). A virtual machine is a guest OS when it is run alongside the host OS.
In certain situations, it can have better performance over full virtualization. But, it can have significantly worse compatibility and portabililty.

### **Hardware Assisted Virtualization**
Similar to full virtualization, but supported at the hardware architecture level. This means that the hardware facilitates building a virtual machines and allows the virtual machine to run in isolation.
---
### How to install Ubuntu
First you need to download your virtualization software. You can download VMware fusion [here.](https://www.vmware.com/products/fusion/fusion-evaluation.html) You can download Fusion or Fusion 10. Either one will work for this tutorial.

Next you will need to download the Ubuntu ISO file. You can download it [here.](https://www.ubuntu.com/download/desktop).

Open up VMware Fusion and this window should pop up.
![pic of step3][step3]

[step3]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step3.png

Click the "+" button on the menu button and click "New..." button as pictured above.

This will take you to the Installation Screen as pictured below.
![pic of step4][step4]

[step4]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step4.png

Click the "Install from disc or image" button or just drag your iso file on top of it.

If you clicked the button, your screen should like this now.
![pic of step5][ste5]

[step5]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step5.png

Go ahead and drag your iso file and it should pop up in the window like so:

![pic of step6][step6]

[step6]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step6.png

Ensure that the “Use Easy Install” box is checked, fill in the required info, then click “Continue”
  *Set your display name
  *Set your account name
  *Set your desired password

![pic of step7][step7]

[step7]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step7.png

Now all you need to do is click the "Finish" Button and your virutalization software (VMware fusion) will set up your virtual machine! (This may take a while).
![pic of step8][step8]

[step8]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step8.png

Once your VM is finished setting up you should be greeted with this screen.
![pic of step9][step9]

[step9]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step9.png

Just click your Username and sign in with the password you set up during the installation process and voila! You have a linux OS on your mac!
![pic of step10][step10]

[step10]:https://github.com/chrisluong12/Digital-Concept-Tutorial/blob/master/images/Step10.png
---








