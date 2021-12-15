# How set up linux for everyday use.
___
## Table of content
* ___What is linux? and Distribution___
* ___Picking a linux Distribution___
* ___Recommended system requirements___
* ___Materials___
*  ___Create a usb boot___
*  ___How boot linux and distribution in a new device___
---
### What is linux?

___My definition___: Linux is a kernel used to power many operating systems and a Distribution are the operating system

___Linux definition based on Google___:Just like Windows, iOS, and Mac OS, Linux is an operating system. In fact, one of the most popular platforms on the planet, Android, is powered by the Linux operating system. An operating system is software that manages all of the hardware resources associated with your desktop or laptop. To put it simply, the operating system manages the communication between your software and your hardware. Without the operating system (OS), the software wouldn?t function.

___Distribution definition based on google___:A Linux distribution (often abbreviated as distro) is an operating system made from a software collection that is based upon the Linux kernel and, often, a package management system.
___
### Picking a Linux Distribution
There are over 150 Linux distribution which can be used depending of your knowledge level. In this project i will be working with Ubuntu because it's the one i work with and its a beginner level distro.
#### Some Examples of diferent level distro:
Distro | Difficulty
-------|-----------
___Ubuntu___ ![ubuntu](images/small%20ubuntu-logo32.png) | ___Beginner___
___Fedora___ ![fedora](images/150px-Fedora_infinity.png)|___Intermediate___
___Arch Linux___ ![arch](images/smallAntu_distributor-logo-archlinux.svg.png) | ___Advance___
___
### Recommended system requirements
* 2 GHz dual core processor or better
* 4 GB system memory
* 25 GB of free hard drive space
* Internet access 
* Either a DVD drive or a USB port for the installer media
___
### Required materials 
* ___A computer with internet___ 
A Computer which is gonna be use to download the distro of your choice.
* ___Rufus___ 
A downloadable application used to create bootable usb flash drives.
* ___usb flash drive___ 
  Where Ubuntu is going to be imported to use in the computer you wish to used it on. 
  ___
  ### How to crate a bootable drive
  * Step 1 
  Download [Rufus](https://rufus.ie/en/) and download the distribution you want in this case is going to be [ubuntu](https://ubuntu.com/download/desktop).
  * Step 2 
  Plug in the flash drive and open Rufus and something like this should show up.
  ![rufus](images/EX.png)
  * Step 3 
Once everything is plug you click in the boot selection click select next to the boot selection. Once you click you will be send to your download folder in which you will choose the Distribution you downloaded finally you click on start at the bottom of the rufus app. 
![ex2](images/ex2.png) and select the ![ex3](images/ex3.png)
 * step 4 
 * Once everything is finally downloaded you can close rufus and eject your usb.
### How boot linux in a new device
* Step 1 
Plug in your flash drives which contains your distro in this case is Ubuntu.
* Step 2
Turn on your device and open your boot menu. You can access this by clicking ESC in your device in in which something like this will be shown.
![bootmenu](images/bootmenu.png) 
* Step 3 
Choose your booting device in this case it's going to be your usb flash drive.
* Step 4 
A window is going to appear with the options to test or download Ubuntu. You can try ubuntu so see if you like it but for this time in gonna download.
![Ubuntu](images/Screenshot%202021-12-14%20142634.png)
* step 5 
* Once everything has been downloaded you can now set up your language, connect to internet, allow third party installation and finally name your computer and add a password.
![step5](images/IMG_5722.jpg)
* Step 6 
Wait for your computer to finish the final downloads 
![finaldownloads](images/IMG_5725.jpg)
You will be ask to log in 
![5767](images/IMG_5727.jpg)

* Step7 
Update your device by using the command `sudo apt update; sudo apt upgrade -y` 
![5730](images/IMG_5730.jpg)
After this you will finally be able to use your device as a regular computer you will be able to Watch, Write and download everything you wanted to. 
![finally](images/IMG_5731.jpg)
![finally2](images/66119053309__6C589023-76C4-4317-878B-085A4CCAF5F9.jpg)
