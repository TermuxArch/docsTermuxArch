'''It is necessary to grant storage permission for Termux on Android 6 and higher. Use 'Settings>Apps>Termux>Permissions>Storage' and set to true.


Execute <code>termux-setup-storage</code> (run <code>[[apt]] update && [[apt]] upgrade</code> to make sure that this tool is available) to ensure:


* That permission to shared storage is granted to Termux when running on Android 6.0 or later,
* That an app-private folder on external storage is created (if external storage exists),
* That a folder <code>$HOME/storage</code> is created,
* The contents of the created <code>$HOME/storage</code> folder are symlinks to different storage folders:

** <code>~/storage/shared</code>
The root of the shared storage between all apps,
** <code>~/storage/downloads</code>
The standard directory for downloads from e.g. the system browser,
** <code>~/storage/dcim</code>
The traditional location for pictures and videos when mounting the device as a camera,
** <code>~/storage/pictures</code>
Standard directory in which to place pictures that are available to the user,
** <code>~/storage/music</code>
Standard directory in which to place any audio files that should be in the regular list of music for the user,
** <code>~/storage/movies</code>
Standard directory in which to place movies that are available to the user,
**<code>~/storage/external</code>
Symlink to a Termux-private folder on external storage (only if external storage is available).

