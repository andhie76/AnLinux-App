This is repo for the main application. If you are looking for the images and scripts used in this app, please visit [here](https://github.com/EXALAB/AnLinux-Resources)

# AnLinux
Run Linux On Android Without Root Access, thanks for the Awesome [Termux](https://github.com/termux/termux-app) and [PRoot](https://github.com/proot-me/PRoot), which make this project possible.

You can find the application on Play Store [Here](https://play.google.com/store/apps/details?id=exa.lnx.a) , or download it on Github if you dont have access to Play Store.



## How it works

The bash script download image over internet, then decompress the image and then mount it using [PRoot](https://github.com/proot-me/PRoot).



## Bootstraping System

Note: Only [Ubuntu](https://www.ubuntu.com/), [Debian](https://www.debian.org/), [Kali](https://www.kali.org/) are bootstrap using the script, others are docker image without modification.

Script located it Scripts/Bootstrap are used to bootstrap the system, to bootstrap a system, simply run:

> ./bootstrap.sh <architecture> /path/to/bootstrap
   
For example: 

> ./bootstrap.sh armhf /home/user/debian/armhf 



## Desktop Environment and GUI

You can now run [LXDE Desktop Environment](https://lxde.org/), currently only [Ubuntu](https://www.ubuntu.com/), [Debian](https://www.debian.org/), [Kali](https://www.kali.org/), [Fedora](https://getfedora.org/) are supported, and only [LXDE Desktop Environment](https://lxde.org/) will work correctly. If you have any suggestion or method about the desktop environment, please open an issue on Github



## Note

1. This app required [Termux](https://github.com/termux/termux-app) to work, it could be install on Play Store. Or download it from [F-Droid](https://f-droid.org/packages/com.termux/) if you dont have access to Play Store

2. About device requirement:

   Android Version : At lease Android Lollipop

   Architeture : armv7, arm64, x86, x86_64

3. Currently only work for command line, GUI are still in progress, please do not blame developers for this.

4. Currently supported distro:

   [Ubuntu](https://www.ubuntu.com/), [Debian](https://www.debian.org/), [Kali](https://www.kali.org/), [Fedora](https://getfedora.org/), [CentOS](https://www.centos.org/), [openSUSE Leap](https://www.opensuse.org/), [openSUSE Tumberweed](https://www.opensuse.org/)

5. For any suggestion or issue, please open an issue on Github.



## Extra License

The author of application icon is [Alpár-Etele Méder](https://www.iconfinder.com/pocike)



## Todo

1. [Arch Linux](https://www.archlinux.org/), [Black Arch](https://blackarch.org/), [FreeBSD](https://www.freebsd.org/), [Slackware](http://www.slackware.com/) support



## Reference

1. [GNURootDebian](https://github.com/corbinlc/GNURootDebian)
2. [debian-noroot](https://github.com/pelya/debian-noroot)
3. [termux-ubuntu](https://github.com/Neo-Oli/termux-ubuntu)