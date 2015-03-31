# drv_sis671_ubuntu-10.x
Driver SIS 671 Ubuntu 10.X

## Installation

+ sudo cp sis671_drv.* /usr/lib/xorg/modules/drivers/
+ sudo cp xorg.conf /etc/X11/
+ sudo reboot

## To know vesa suport
sudo hwinfo --framebuffer | less
