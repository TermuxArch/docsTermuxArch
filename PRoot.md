Package: proot 

Description: Emulate chroot, bind mount and binfmt_misc for non-root users 

Homepages: [https://proot-me.github.io](https://proot-me.github.io)

[https://github.com/proot-me/PRoot](https://github.com/proot-me/PRoot)


PRoot is a user-space implementation of <code>chroot</code>, <code>mount --bind</code>, and <code>binfmt_misc</code>. This means that users don't need any privileges or setup to do things like using an arbitrary directory as the new root filesystem.


Benefits of PRoot include running Linux operating systems in Termux on a smartphone and tablet in Android and Chrome. Termux offers Linux operating system software for your device in the following flavors:


1. [Arch](Arch)
2. [Debian](https://people.debian.org/~wookey/bootstrap.html)
2. [CentOS](https://www.centos.org/download/)
2. [Fedora](https://wiki.termux.com/wiki/Fedora)
2. [FreeBSD](https://www.freebsd.org/where.html)
2. [Gentoo](https://www.gentoo.org/downloads/)
2. [GhostBSD](http://www.ghostbsd.org/download)
2. [Kali Nethunter](https://wiki.termux.com/wiki/Kali_Nethunter)
2. [Manjaro](https://manjaro.org/get-manjaro/)
2. [Mint](https://linuxmint.com/download.php)
2. [OpenBSD](https://www.openbsd.org/ftp.html)
2. [Oracle](http://www.oracle.com/technetwork/server-storage/linux/downloads/default-150441.html)
2. [Parabola](https://wiki.parabola.nu/Main_Page)
2. [Red Hat](https://access.redhat.com/downloads/)
2. [Slackware](https://wiki.termux.com/wiki/Slackware)
2. [Ubuntu](https://people.debian.org/~wookey/bootstrap.html)


This list of operating systems that run in Termux is not all-inclusive. Please add Linux distributions to this list if you have tested them. Also, if you can add or improve any of the installation scripts, the community will be very grateful.

= General Overview of PRoot =
PRoot uses `ptrace` system call to fake root privileges. That means it traces each of its child processes to interpret and convert system calls made by the child processes.


PRoot command can be used to execute one command from fake chroot or start a shell session. The latter will be useful for virtualizing guest root file systems of other operating systems.


If you know some command line, run <code>proot --help</code> for a complete help screen. You are advised to learn Linux Command line basics anyway before using any guest OA rootfs.


Also, PRoot only virtualizes the root filesystem tree and not an entire OS. Don't expect things like inserting a kernel module to work.


A performance penalty is observed when you virtualize a rootfs using proot, which is not of course as slowness as using emulators. However, when required packages are available in the Termux ecosystem, use them because it is easier and faster.


Do not expect everything to work though. Some blogs may mislead people as if they can hack (crack) computers in Termux or using other tools such as Kali Linux. However, without knowing system internals and programming, it is hardly possible to crack into systems. At worst it may be legally dangerous. Don't expect to do penetration testing in termux unless you are a penetration tester.


= Settings =
To be used if <code>[[termux-exec]]</code> and <code>proot</code> are installed:
   unset LD_PRELOAD
   export LD_PRELOAD=$PREFIX/lib/libtermux-exec.so


'''How to unset?'''


if you are going to launch or execute startup script containing proot command so before that you will have to unset LD_PRELOAD first (if you have installed termux-exec at the same time) otherwise you will get an error. Its very easy to unset LD_PRELOAD by executing <code>unset LD_PRELOAD</code>


'''How to set back?'''


Now if you completed your proot work and you want to use your termux so now you have two options to again set/export LD_PRELOAD :-

1) Just open a new session and exit from the previous session so now your LD_PRELOAD will be set automatically with the new session.

2) If you don't want to open new session because of any reason, you can also export or set LD_PRELOAD path in the same session by executing this <code>export LD_PRELOAD=$PREFIX/lib/libtermux-exec.so


