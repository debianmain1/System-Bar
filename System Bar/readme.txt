Conky System Bar For conky 1.10 ONLY!!
===========

 System Info widget for use with Conky
 by debianmainuser (07/11/2015 <debianmainuser@gmail.com>)

	Based off of Basic V0.7 by Moob (20-10-2015 <moobvda@gmail.com>)
	This widget draws the Wired Conky interface to display system information

        Used some mods from soundrolf (system tab)

	Start conky with '-q' to get rid of conky statfs64 messages when a usb stick/disk is unmounted.-
	Prerequisites : lm-sensors, Conky version 1.10.0

	debianmainuser	Modified function: conky_wired_tab_system for system info-- OS, Kernel, CPU Type & Speed.
	07/11/2015      Added: conky_wired_tab_cpu_temp & gpu_temp for CPU temp & GPU temp. Locked CPU Load & Temp to 4 CPU's 
                        (modify if you need less info)
                        Added: conky_wired_bar_temp to support temp bar functions. (replaces "%" with "C". 100 = 100C)
                        Removed: Battery tab  (for desktop use only)
                        Removed: Radio tab
                        Added: semi-transparent surrounding box to allow monitor to be seen with any wallpaper
                        Changed: Default font type - added new color "purple"
                        Sized for 1920x1080 window (change max height below for smaller monitors-designed for Gnome3 top panel use)
                        More notes are in the System_Bar.lua

INSTALLING:

Of course you have unpacked if you are reading this :)  Just drop the conky & fonts into your /home .conky & .fonts then start with the conky-startup.sh
You can startup everytime by adding the startup script to your Startup Applications..

chmod 755 ~/.conky/conky-startup.sh if you need to.

And modify this to whatever you want...PLEASE CREDIT the authors (Moob, soundrolf & debianmainuser) if you mod & repost this.

ENJOY!!!!
