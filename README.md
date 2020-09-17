# NETGEAR_Nighthawk_AC1900

This is the Linux driver for NETGEAR Nighthawk AC1900 (A7000) WiFi USB adapter.

## Working with Kernel 4.19 on Debian Buster

I have updated this driver to work on kernel 4.19. I will continue to maintain this driver here.

## Build method
Open your terminal and run the following to download, build, install, and then reboot in order to use
the driver.

    $ git clone https://github.com/byrnedj/NETGEAR_Nighthawk_AC1900.git
    $ cd NETGEAR_Nighthawk_AC1900
    $ make
    $ sudo make install
    $ sudo reboot now


## Build info

See below for the original author's build instructions.

## prerequisite
The kernel of you Linux system should not be higher than 4.4 otherwise you need to download Linux kernal 4.4 on website http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.4-wily for kernal compatible with your computer. For example

    $ wget http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.4-wily/linux-headers-4.4.0-040400_4.4.0-040400.201601101930_all.deb
    $ wget http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.4-wily/linux-headers-4.4.0-040400-generic_4.4.0-040400.201601101930_amd64.deb
    $ wget http://kernel.ubuntu.com/~kernel-ppa/mainline/v4.4-wily/linux-image-4.4.0-040400-generic_4.4.0-040400.201601101930_amd64.deb
    $ cd your_download_path
    $ sudo dpkg -i *deb
After this, you need to reboot and select the 4.4 kernal before entering your Linux system.

## Build method
Open your terminal and run

    $ git clone https://github.com/RichardYao1995/NETGEAR_Nighthawk_AC1900.git
    $ cd NETGEAR_Nighthawk_AC1900
    $ make
    $ sudo make install
