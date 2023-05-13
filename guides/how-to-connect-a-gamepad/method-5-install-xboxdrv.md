
description: >- You may need to use xboxdrv to make Dualshock and Dualsence to work.

# Method 5: Install XboxDrv

This method is only for Linux. This will not work on Windows or Mac

#### Step 1: Open terminal with CTRL+ALT+T.

#### Step 2: Install XboxDrv with the following command/s.

ubuntu/debian
>  sudo apt-get install xboxdrv 

fedora/redhat

>  sudo dnf install libevdev libevdev-devel
>  sudo dnf install xboxdrv (fedora/redhat)

arch/manjaro

>  sudo pacman -S base-devel git dkms
>  sudo pacman -S yay
>  yay -S xboxdrv-git

#### Step 3: Start XboxDrv

> sudo xboxdrv --detach-kernel-driver


