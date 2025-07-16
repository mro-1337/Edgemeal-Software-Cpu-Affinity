Get and Set CPU Affinity Programs

===============
  Terms of Agreement
===============

By using the included Freeware, you agree to the following terms...

1) You may use this software freely and with no charge.

2) You MAY NOT redistribute this software (for example to a web site).

========
 Disclaimer
========
Users of this software must accept this disclaimer of warranty:
The software is supplied as is. The author disclaims all warranties,
expressed or implied, including, without limitation, the warranties of
merchantability and of fitness for any purpose. The author assumes no
liability for damages, direct or consequential, which may result from the
use of said software.

 Install:
* These programs are made for administrator user, there is no install.
* Extract archive to a new folder, read the included Help and run the exe.
* Note: Intel Hyperthreaded cores are not supported!

PriFinitty Version 2.x and PriFinitty 64 Beta 1.0
* Set CPU Affinity and Priority on multiple files manually or automatically.
* Support up to 8 real CPU cores, 5 favorite profiles, CPU usage graphs per program and more...
Set Affinity II  - v1.041 (52 KB - Aug 02, 2010)  Screen Shot - Version History
MD5: 8EA30E4FB5205995A24903AC0B7851EB
* Supports up to four (real physical) CPU cores, 1 favorite profile.
* Set CPU Affinity manually or automatically.
* Displays total CPU usage in tray icon, CPU usage and average CPU usage per core in program.

Set Affinity II  - v1.040 (52 KB - June 19, 2010)
MD5: DC93B487E2781B582619F51119B77A45

Set Affinity 64  BETA  v1.01 (53 KB - July 05, 2010) - Note:This is a 32-bit compiled program!
MD5: 472918CB431DD7A6A98AF2BD4FF9F424
* For testing on Windows 7 64-bit.
* v1.01 - File icons for 64-bit programs should now be seen, couple minor changes.

Get and Set Affinity v2.38 (110 KB - Sept. 01, 2009) Screen Shot - Version History
MD5: 3339E9F7A6AE04BD18D13D53BA00F363 - ReCompiled Oct. 20, 2010 (see history)
* Supports two CPU cores only! (one Dual core).
* Set CPU Affinity manually or automatically.
* Set Priority for running programs manually.
* Set Windows XP Services manually or a group of services using profiles.
* Graph CPU usage of individual programs.
* Displays CPU usage as a dual bar graph in system tray.


Vista/Windows 7
* When run on Vista/Win7 you will need to run the program as administrator  to see & set  most running files.
* As administrator  with UAC enabled you will get a UAC prompt when launching the program and UAC will also block the Start with Windows option!
* Also, the drive/folder the program runs in must allow folders & files to be created/written to.
Make Vista launch UAC restricted programs at startup with Task Scheduler
Run UAC restricted programs without the UAC prompt
 Special Notes & User Feed Back:

Thanks to everyone who has sent us feedback!

Just wanted to let you know of a handy way to work around the UAC prompting for starting PriFinitty and others with Windows. You can create a scheduled task to run at logon with “highest privileges” thus bypassing the prompt. Method found here: Make Vista launch UAC restricted programs at startup with Task Scheduler
 - Antony

Thanks for the feedback!
I had the "CPU Usage Query Failed" error on Windows 7 64bit.
Opening CMD.EXE and executing lodctr /R did it, now setaffinity64 runs again.
Kind regards, Baltzer
Thanks for the feedback!

I tried Affinity 64 (beta 1.0) program it's working very well, and what is interesting the icons for the 64 bit  programs reminds me to AtariST icons in monochromatic mode even it's obviously icon of Macintosh classic, many thanks for additional effort and i wish you all the best!
KiLLeR2K
You're seeing a default icon that is used when Affinity64 is unable to retrieve a files icon or the .Exe file doesn't have an icon. In v1.01 the default icon has changed and the program should now be able to get icons for most 64-bit programs.

Affinity 64 is based on Set Affinity II and I haven't tested it much at all.
Cheers, Ed

I've been using Set Affinity II for some time now.
On Vista sp1 x64 home premium with an intel 9540 (4 cores).
 
It's great and works fine.
Just one little annoying thing: it cannot automatically startup because vista blocks it.
Something to do with not properly signed applications. 
Maybe this could be helped when installing the program with a proper installation tool.
Guus

I would like to make the programs more Vista/Win7 friendly but I have no plans to do so. Most likely the program will have to be run as Administrator type user and have UAC disabled for the Start with Windows option to work.
Cheers, Ed
I used Set Affinity II for a couple of months - using Vista 32 - and it's been amazing.
Upon start now I get the following error:
"CPU Usage Query Failed"
Any idea what it means please?
Regards, Antonio
Awhile back a WinXP user emailed me with the same problem. IIRC when he ran Windows "Performance" monitor (in admin tools section) the CPU usage didn't work there either.

He said he fixed it using the info found on MS site here,
How to manually rebuild Performance Counter Library values

I've never had the problem and don't use Vista or Win7, so really can't offer any other help except to try the newer Set Affinity II v1.039 as it should bypass and disable CPU usage in the program if it fails to work.

Just a note, our PriFinitty2 program uses a different approach but only shows the total CPU usage, or CPU usage per program.
HTH, Ed

