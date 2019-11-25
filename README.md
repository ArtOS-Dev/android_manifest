# LotusOS #

<img src="https://raw.githubusercontent.com/Lotus-OS/android_manifest/pie/IMG_20191122_201827_999.jpg"> 

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u https://github.com/Lotus-OS/android_manifest.git -b pie
```

Then to sync up:
================

```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Compilation of Lotus OS:
====================

From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch lotus_<devicecodename>-userdebug
make bacon -j$(nproc --all)
```
-----------------------------------------------------------------------------

 Credits:
=======
 * [**CyanogenMod**](https://github.com/Cyanogenmod)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSP**](https://android.googlesource.com)
 * [**Evolution-X**](https://github.com/Evolution-X)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**AOSCP**](https://github.com/AOSCP)
 * [**NitogenOS**](https://github.com/NitogenOS)
 * [**MSM-Xtended**](https://github.com/MSM-Xtended)
 * [**DescendantOS**](https://github.com/Descendant)
 * [**BootleggersROM**](https://github.com/BootleggersROM)
 * [**AICP**](https://github.com/AICP)
 
-----------------------------------------------------------------------------
