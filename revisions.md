TermuxArch now configures, installs and updates Arch Linux in Termux PRoot for aarch64 and armv7 without asking the user any questions.  All the required information is ascertained from the device and wireless connection without any requirement for user interaction.  Improvements include:

.bash_logout implemeted
addcdtd created
addcdth created
addkeys refined
bloom option revised
exec proot added 
ktest.sh refined
motd refined
moto created
option run dropped
printconfigq () renamed printconfigup () 
trimmed motd
trim refined
pacman -Rc added
pc and pci header added
printtail revised
spinner added

TermuxArch v1.7

Arch Linux Termux install script for Amazon Fire OS, Android and Chromebook.  See https://sdrausty.github.io/TermuxArch/docs/install for installation instructions.
---
TermuxArch now configures, installs and updates Arch Linux in Termux PRoot for aarch64 and armv7 without asking the user any questions.  All the required information is ascertained from the device and wireless connection without any requirement for user interaction.  Improvements include:

* Added more support for Android 8,
* startarch $@ expansion and options updated,
* addkeys () created,
* addlangq () deprecated from runfinishsetup (),
* copystartbin2pathq () deprecated from copystartbin2path (),
* Clean added to dependsblock () for git repositories,
* `tzselect` deprecated in favor of `export TZ=$(getprop persist.sys.timezone)` eliminating the need to edit and add TZ information to the `.bash_profile` file,
* `if [ $fstnd ]; then` and `until ftchstnd;do` implemented to makesystem () eliminating the need to edit the mirrorlist file.

TermuxArch v1.6

Arch Linux Termux install script for Amazon Fire OS, Android and Chromebook.  See https://sdrausty.github.io/TermuxArch/docs/install for installation instructions.
---
Default install for aarch64 and armv7 now configures, installs and updates Arch Linux in Termux PRoot without asking the user any questions.  All the required information is ascertained from the wireless connection and device without any requirement for user interaction.  mprovements include:

* Added more support for Android 8,
* startarch $@ expansion and options updated,
* addkeys () created,
* addlangq () deprecated from runfinishsetup (),
* copystartbin2pathq () deprecated from copystartbin2path (),
* Clean added to dependsblock (),
* `tzselect` deprecated in favor of `export TZ=$(getprop persist.sys.timezone)` eliminating the need to edit and add TZ information to .bash_profile file,
* `if [ $fstnd ]; then` and `until ftchstnd;do` implemented to makesystem () eliminating the need to edit the mirrorlist file.

TermuxArch v1.6

Arch Linux Termux install script for Amazon Fire OS, Android and Chromebook.  See https://sdrausty.github.io/TermuxArch/docs/install for installation instructions.
---
* $bin and makebin () depreciated in favor of $startbin and makestartbin ()  
* Added addexd () export DISPLAY=:0 PULSE_SERVER=tcp:127.0.0.1:4712
* Added alias pcs='pacman  --Ss --color=always'
* Added help to `startarch`
* Added help to `we`, Watch Entropy
* Added pst () making the proot statement modular
* Created addtrim () 
* makefinishsetup () rewritten
* makestartbin () rewritten to accommodate hush-login and $prootstmnt 
* Script stability improved
* Test harness `thstartarch` for `startarch` created
* Watch Entropy `we` expanded

TermuxArch v1.5

Arch Linux Termux install script for Amazon Fire OS, Android and Chromebook.  See https://sdrausty.github.io/TermuxArch/docs/install for installation instructions.
---
* $HOME/.chushlogin created
* $HOME/.hushlogin created
* Advanced usage refined.
* Buildin statements refined
* Created nameinstalldir () $installdir to ease installing in alternative root directories.
* Entropy user printout statements updated.
* echoSpecialParameters () added to `systemmaintenance.sh`.
* Watch Entropy helper, `we` modularized and given options:  Install `bc` added, if not present;  Detect install architectures between Arch Linux and Android added to watch entropy.

TermuxArch v1.4

Arch Linux Termux install script for Amazon Fire OS, Android and Chromebook.  See https://sdrausty.github.io/TermuxArch/docs/install for installation instructions.
---
* addmotd () refined.
* addbashrc () refined.
* Entropy generation refined.
* For loops softened.
* Minus signs removed from option usage.
* Printout statements refined and expanded.
* Refresh option exceptions added.
* `startarch` changed to `startarch$tarch`.
* Watch entropy `we` command added.
* Quited entropy generation.

TermuxArch v1.3

Arch Linux in Termux install script for Amazon Fire OS, Android and Chromebook.  See https://sdrausty.github.io/TermuxArch/docs/install for installation instructions.
---
addmotd () refined
addbashrc () refined
entropy generation refined
for loops softened
minus signs removed from option usage 
printout statements refined and expanded
refresh option exceptions added
`startarch` changed to `startarch$tarch`
watch entropy `we` command added
quited entropy generation
-------------------
makepkg.diff applied
login options added to startarch
refresh option added to setupTermuxArch
this option just refreshes the TermuxArchthis option just refreshes the system filessystem files
default answer added to rmbloomq ()
`pacman`  --color always added to pacman statements
printout statements updated
`ce` updated
`tour` created
read questions updated
instructiond expabded for vim nvim
-------------------

continue statements reimplemented in ftchstnd
entropy generation revised
locale instructions added
locale question  revised
entropy generation 
-------------------
proot kill-all
packey install added
packey install instructions added
mirror instructions added to mirror file
lr ls -alR BASH alias added
ae available entropy
ce create entropy 
ces create entropy start
