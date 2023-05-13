---
description: >- You may need to use xboxdrv to make Dualshock and Dualsence to work.
---
# Method 5: Install XboxDrv

This method is only for Linux. This will not work on Windows or Mac

#### Step 1: Open terminal with CTRL+ALT+T.

![image](https://github.com/gustavsgoldbergs/Controllable-Documentation/assets/75438804/44519303-be9d-479e-9f71-b71c4ea51034)

#### Step 2: Install XboxDrv with the following command/s.

>  sudo apt-get install xboxdrv (ubuntu/debian)
>  sudo dnf install libevdev libevdev-devel
>  sudo dnf install xboxdrv (fedora/redhat)
>  sudo pacman -S base-devel git dkms
>  sudo pacman -S yay
>  yay -S xboxdrv-git (arch/manjaro)\

#### Step 3: Start XboxDrv

> sudo xboxdrv --detach-kernel-driver


