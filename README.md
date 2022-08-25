# RTL8812au_for_wifi

    Dell core duo desktop (wired only) with Ubuntu 18.04.1 (up-to-date via: sudo apt-get update)
    Plugin the AC600, turn on desktop, login.
    Make sure you have required build package (via: sudo apt-get install linux-headers-generic build-essential git)
    git clone https://github.com/gnab/rtl8812au (download with your wired connection. Also, I did this in ~/Downloads dir to keep my home dir clean)
    cd rtl8812au
    sudo make (Only see one or two warnings saying that some code will never be executed, ignore them)
    sudo make install (do this only after the driver is built in step 6)
    Reboot, unplug your wired network line.
    Log back in and click upper-right corner down-triangle, click wireless connection and set it up.

My Ubuntu box goes wireless now. That's how I did it. Hope this helps!
