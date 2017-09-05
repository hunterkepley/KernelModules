## Information
Random kernel modules I've made

## Prerequisites
You need kernel-devel and kernel-headers! Make sure they match your kernel version [uname -r will tell you]

## Compiling
Run the makefile [make]

## Installing/Removing
insmod file.ko to install the module
rmmod to remove

## Credits
I used [this online guide](http://www.tldp.org/LDP/lkmpg/2.6/html/lkmpg.html) for a few of the modules to learn the basics.

The ones that used it are stated in at least one .c file [the module's source]

The ones that do not have that stated anywhere are made by myself
