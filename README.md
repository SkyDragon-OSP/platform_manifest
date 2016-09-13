
*** SkyDragon Open Source Project ***


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
