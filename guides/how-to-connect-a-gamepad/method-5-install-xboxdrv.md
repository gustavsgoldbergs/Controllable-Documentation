
# Method 5: Install XboxDrv

This method is only for Linux. This will not work on Windows or Mac. 
You may need to use xboxdrv to make Dualshock and Dualsense to work.


#### Step 1: Open a terminal

#### Step 2: Install XboxDrv with the following command/s.

Ubuntu/Debian
>  sudo apt-get install xboxdrv 

Fedora/Red Hat linux

>  sudo dnf install libevdev libevdev-devel &&
>  sudo dnf install xboxdrv 

Arch linux/Manjaro

>  sudo pacman -S base-devel git dkms &&
>  sudo pacman -S yay &&
>  yay -S xboxdrv-git

#### Step 3: Start XboxDrv

> sudo xboxdrv --detach-kernel-driver


