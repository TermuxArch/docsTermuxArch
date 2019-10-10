##### -rwxrwx--- [setupTermuxArch.sh](https://sdrausty.github.io/TermuxArch/setupTermuxArch.sh)  
##### -r--r--r-- [setupTermuxArch.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/setupTermuxArch.sh)

#### Prerequisites: minimum of about 1GB free in userspace on device, if you want to have some fun on your device and working knowledge of vimtutor is recommended.  There are many ways to run this setup script on device.  Please use the bash shell for installation and execution of [setupTermuxArch.sh](https://raw.githubusercontent.com/sdrausty/TermuxArch/master/setupTermuxArch.sh).  Here are some methods:

(1) This method can be run by tapping [this link](https://sdrausty.github.io/TermuxArch/setupTermuxArch.sh) which should download `setupTermuxArch.sh` into your `~/storage/downloads/` directory on your smartphone and tablet.  If short tapping [this link](https://sdrausty.github.io/TermuxArch/setupTermuxArch.sh) does not download `setupTermuxArch.sh` from your web browser, try long tap and choose download file from the popup menu.  Install Arch Linux in Termux PRoot by simply running the next line of code in Termux: 

```
bash ~/storage/downloads/setupTermuxArch.sh

```  
Ensure Termux storage is correctly setup for this method to work.  It is necessary to grant storage permission for Termux on Android 6 and higher. Use 'Settings>Apps>Termux>Permissions>Storage' and set to true.  Then execute `termux-setup-storage`.  See [Termux Setup Storage](TermuxSetupStorage) for details.  You want Termux storage to be set up correctly anyway, since it is also used by Arch Linux in Termux. 


(2) Run the following command lines in bash to install Arch Linux in Termux on your device.  Run each of the following command lines separately. Running them all at once may generate errors; Hint, copy and paste the following into the Termux window: 

```
pkg install git
cd && git clone https://github.com/sdrausty/TermuxArch
bash TermuxArch/setupTermuxArch.sh

```
Should you choose this option, the preferred method to work on projects at GitHub, clone to native space on device when you can.  See ["Notice to Collaborators"](https://sdrausty.github.io/TermuxArch/NOTICE.html) for more information about collaborating.  This repository uses submodules.  To get all the pieces run `scripts/maintenance/pullTermuxArchSubmodules.sh` in the root directory after cloning.  


(3) Copy and paste the following command lines into your Termux bash command shell:

```
pkg install wget
wget https://sdrausty.github.io/TermuxArch/setupTermuxArch.sh
bash setupTermuxArch.sh

```

#### To add Archstrike and Blackarch distributions follow these steps.  Use https://sdrausty.github.io/TermuxArch/ to install, update and configure Arch Linux on device first. 

Then edit your /etc/pacman.conf by adding:

[archstrike] 

Server = https://mirror.archstrike.org/$arch/$repo

[blackarch] 

Server = http://blackarch.org/blackarch/$repo/os/$arch


Next run pacman -Syu to update your repository listing.  To install either distribution, run one of these commands:

pacman -S archstrike --needed

pacman -S blackarch --needed

:: There are 663 members in group archstrike: ~2G download (~6G on device)

:: There are 1602 members in group blackarch: ~5G download (~16G on device)

That's a lot of pentesting.  If you don't desire this much pentesting, don't install everything. 

## To search only for packages, use `pacman -Ss {query}`.  To install, use `pacman -S {package}`. 

Enjoy 😀 

[![screenshot_20180413-172406](https://user-images.githubusercontent.com/27742457/38758637-ec0ff0dc-3f3f-11e8-802c-82bc511cde88.png)](https://TermuxArch.github.io/docsTermuxArch/install)

This setup script will attempt to set Arch Linux up in your Termux.  When successfully completed, you will be at a bash prompt in [Arch Linux](https://archlinuxarm.org) in [Termux](https://termux.com/) using an Android smartphone, tablet or a Chromebook.

[![Join the chat at https://gitter.im/termux/termux](https://badges.gitter.im/termux/termux.svg)](https://gitter.im/termux/termux)

* Comments are welcome [here](https://github.com/sdrausty/TermuxArch/issues) ✍

* Pull requests are welcome [here](https://github.com/sdrausty/TermuxArch/pulls) ✍

Thanks for making this project work; Please contribute 🔆  See [Notice to Collaborators](https://sdrausty.github.io/TermuxArch/NOTICE.html) for more information.  [PRoot](./PRoot) has more information about Linux on device in Termux.

