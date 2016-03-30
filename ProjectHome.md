### iTunes installer for Windows XP x64bit. ###

Two folders - version 8  and version 10

All files have been scanned before uploading to github for viruses etc. Use at your own risk. Any issues arising from use of these files
is the users responsibility. All errors are your fault.

:)

Just covering myself.

### IMPORTANT ###

I will NOT provide any help if you have issues. Use google - plenty of links on apples support forums that should answer your questions.

### VERSION 10.1.1 ###

ipod services work fine in version 10.1.1. Only new issue I have is I cant backup anything, keeps crashing.
install in the following order
- appleapplicationsupport
- appledevicesupport64
- itunes64

I have included ipodservice x64-bit just incase people need it.

### VERSION 10 and below ###

### QUICK (LAZY) ###

quick way is to install AppleMobileDeviceSupport64, then iTunes64 in folder version 10. Then wait until you get a window allowing you
to ignore the ipod service module. Then find folder ipod in your program files folder, and replace with the one in itunes-ipodservice.

### MANUAL ###

version 8 - install this version first. Then find in your program files folder a folder named ipod. Copy or rename that folder and contents
so it is safe.

version 10 - make sure you have installed version 8 and copied or renamed the ipod folder in your program files folder. Then install
AppleMobileDeviceSupport64, then iTunes64. At the end you will get error windows pop up saying ipod service module cant start. Keep
closing them until itunes gives you the option to ignore. Once all is installed find the new ipod folder, replace ipodservice with the one
you copied or renamed. If you cant delete it, end the service by opening Windows Task Manager.

It then works fine.

### MORE PROBLEMS? ###

If you still have issues read this blog post - http://skunkwerks.wordpress.com/2008/04/13/getting-itunes-to-work-with-windows-xp-x64/

I had problems with windows thinking the ipod was a camera - I had to follow the Troubleshooting iTunes / iPhone Link/Sync section. This
sorted everything out.