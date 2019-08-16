# Desktop-From-Scratch-Guide
   ~~~~~~This is a totally noob guide to create a basic desktop env as I embark on a journey of my own.~~~~~~

First things first, the purpose of this guide is to HELP YOU install a basic OS and desktop environment. Regarding the guide, we will be using Arch Linux as our linux distro, pacman (comes with arch) as our package manager, vim as our text editor, and X or Xorg as our display server/ manager. X isn't a desktop env alone but as this guide gets updated, so will the resources we use to get that environment up and running. 


Step 1: Backup your stuff

  Super easy task but some of us forget because we get so excited to start with the fun stuff. Do it. If you want to scrap your installation and revert to your old setup, you'll thank yourself for taking the necessary precaution. However, if you are truly starting from scratch on a machine with no partitions, then you're good. 
  

Step 2: Follow the installation guide wiki
https://wiki.archlinux.org/index.php/installation_guide

  The wiki is a super useful tool for installing a basic Operating System (OS). You'll learn things like package managers, file systems, and more about your machine than you'd currently know! What makes an OS? How important is documentation on programs/software? (Trick question, it's important, SUPER important. Like you'll be so incredibly happy that you can follow something concrete instead of having to figure it out yourself.)
  
  So one thing the wiki doesn't tell you is partitioning your disks properly, it just gives you a table with what you should have based on your system. If you run BIOS legacy like I was, you'll find that using the cfdisk command is way easier than fdisk /dev/sdX. cfdisk is a linux partition editor, that means that instead of typing specific commands that you may not know, you can just navigate through this editor to do what you set out to do. 
  
  Here's more info: https://en.wikipedia.org/wiki/Cfdisk
  
  
Step 3: After Arch

  With the successful installation of Arch, we now have a fully operational computer! But what do we do next? Only a black command line is visible and we have no idea what has happened. Well here's the rundown, your operating system is fully functional and everything went according to plan. Arch is a "minimal" OS with no fluff, that means that there is no desktop, no GUI, no nothing, just the linux kernel and everything it needs to run at minimal. Now our job is to turn this machine from a hackers home to a normal users paradise. We will do so by first installing X.
  
  
Step 4: X and the GUI

  As stated before, X or Xorg is a display "manager" it isn't a desktop itself as much as it is the foundation of a desktop. Imagine a house, we have the ground layer (Arch), foundation above the ground (X), then the walls (Gnome, KDE, i3), and finally the decoration or the flex of the house (what we do with the previous). 
  
Step 5: Programs to make your life easier

   The defaults are well... basic. If you want a more efficient system then I'd recommend to use:
      1. File Manager
      2. Browser (Firefox or DuckDuckGo)
      3. Rofi for program running and searching
