
*** SkyDragon Open Source Project ***


* This is my Personal/SkyDragon-Team-Only rom build, not for the public/sharing, don't flame me for "kanging", all's available here for you too *


Android 7.0.0_R6


*Get The Source*

	$ mkdir ~/skydragon
	$ cd ~/skydragon
	$ repo init -u https://github.com/skydragon-osp/platform_manifest -b n
	$ repo sync


*To Build*

	$ source build/envsetup.sh
	$ make clobber
	$ lunch
	$ make -j `getconf _NPROCESSORS_ONLN` otapackage
