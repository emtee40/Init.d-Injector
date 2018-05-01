# Init.d Injector
Injects init.d support:
Via post-fs-data script if using magisk
Via init script if system install (also installs setools by Xmikos (https://github.com/xmikos/setools-android))
Built with Unity installer by Zackptg5 (https://github.com/Zackptg5/Unity) and AnyKernel2 by Osm0sis (https://github.com/osm0sis/AnyKernel2/)
[More details in support thread](https://forum.xda-developers.com/android/software-hacking/mod-universal-init-d-injector-wip-t3692105).

## Change Log
### v1.3 - 5.xx.2018
* Redid ak2 logic - redo scripting (uses initd.sh rather than sysinit), has capability to run init.d scripts as post-fs-data (default) and late_start (add '-ls' to the end of the name of it), use this logic for all system installs
* Magisk uses magisk boot scripts but does the same thing
* Update it so it'll work with sysover if user chooses
* Unity v1.5.4 update

### v1.2.1 - 4.26.2018
* Unity v1.5.3 update

### v1.2 - 4.16.2018
* Unity v1.5.2 update

### v1.1 - 3.17.2018
* Run all scripts except live boot as late start in magisk due to magisk mount occuring after post-fs-data script

### v1.0 - 3.16.2018
* Initial rerelease

## Source Code
* Module [GitHub](https://github.com/Zackptg5/Init.d-Injector)
