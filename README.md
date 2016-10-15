
*** SkyDragon Open Source Project ***


Currently based on: Android 7.0.0_R14

* This is my Personal/SkyDragon-Team-Only rom build 
* Not for the public/sharing
* Don't flame me for "kanging" 
* All's available here for you too
* Credits/Many thanks to: 
* - PureNexusProject 
* - Uberroms


*Get The Source*

	$ mkdir ~/skydragon
	$ cd ~/skydragon
	$ repo init -u https://github.com/skydragon-osp/platform_manifest -b n
	$ repo sync -f --force-sync


*To Build*

	$ source build/envsetup.sh
	$ make clobber
	$ lunch
	$ make -j `getconf _NPROCESSORS_ONLN` otapackage
