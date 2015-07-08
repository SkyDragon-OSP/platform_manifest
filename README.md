
*** SkyDragon Open Source Project ***

Android 5.1.1_R6

*Get The Source*

	$ mkdir ~/skydragon
	$ cd ~/skydragon
	$ repo init -u https://github.com/skydragon-osp/platform_manifest -b master
	$ repo sync
	
*To Build*

	$ source build/envsetup.sh
	$ make clobber
	$ lunch aosp_shamu-userdebug
	$ make -j `getconf _NPROCESSORS_ONLN` otapackage
