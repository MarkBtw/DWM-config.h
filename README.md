# DWM-config.h
My tweaked DWM config.h file.


First of all; make sure to put all your Suckless Software into one directory, mine is named /Suckless/.
I will be refering to this directory with "YourSucklessDirectory", so replace that part with the name of your directory.
Also make sure to create a BACK-UP in case you make a big oof.


Now, to use my custom fork of DWM, simply follow these steps:




Step 1: Open your Terminal.

Step 2: Do "git clone https://github.com/MarkBtw/DWM-config.h.git".

Step 3: Do "cd DWM-config.h".

Step 4: Do "sudo cp config.h ~/YourSucklessDirectory/dwm-6.2/config.h".

Step 5: Do "cd ~/YourSucklessDirectory/dwm-6.2/"

Step 6: Do "sudo make clean install".

Step 7: Now, delete the repository you cloned, restart DWM, and you should now have my custom DWM fork, if any errors occur read below.



ERROR FIX
=========

Try the following If it doesn't let you write to your "YourSucklessDirectory/DWM-6.2/config.h" file:

Step 1: Do "cd DWM-config.h"

Step 2: Do "sudo cp config.h ~/YourSucklessDirectory/dwm-6.2/config.def.h".

Step 3: Do "cd ~/YourSucklessDirectory/dwm-6.2/".

Step 4: Do "sudo cp config.def.h config.h".

Step 5: Do "sudo make clean install".

Step 6: You should now have my custom DWM fork.
