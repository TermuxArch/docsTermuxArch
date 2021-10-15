To install https://blackarch.org do the following:
1) Install, update and configure Arch Linux using [`setupTermuxArch.sh`](https://sdrausty.github.io/TermuxArch/setupTermuxArch.sh).
2) Add the next lines to the end of the /etc/pacman.conf file:
```
[blackarch]
Server = http://blackarch.org/blackarch/$repo/os/$arch
```
3) Run `pacman -Syu`.
4) Run `pacman -S archstrike --needed`.

Does anyone want to install:
1) https://www.archstrike.org on device in Termux?
2) https://www.blackarch.org on device in Termux?

First use https://sdrausty.github.io/TermuxArch/ in install, update and configure Arch Linux on device.

Then edit your /etc/pacman.conf by adding:

[archstrike]
Server = https://mirror.archstrike.org/$arch/$repo

[blackarch]
Server = http://blackarch.org/blackarch/$repo/os/$arch

Next run pacman -Syu to update the repository listing. To install:

Run pacman -S archstrike --needed

Run pacman -S blackarch --needed

:: There are 663 members in group archstrike:
:: There are 1602 members in group blackarch:

Enjo
 😀
That's a lot of pentesting.

