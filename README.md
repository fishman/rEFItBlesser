# rEFItBlesser

This is a customized version of rEFItBlesser to work with rEFInd

[1] http://refit.sourceforge.net/doc/c4s4_safesleep.html

# Why?

The Macbooks go into Deep sleep mode or hibernate after an hour. You can change that with:

    sudo pmset -a autopoweroffdelay seconds

Unless the startup disk is set to your Macintosh HD, your system will not be able to wake up from sleep. To work around this problem rEFIt installs rEFItBlesser

# Install

To install simply copy the folder into

    /Library/StartupItems

and run

    sudo chown -R 0:0 /Library/StartupItems/rEFItBlesser
