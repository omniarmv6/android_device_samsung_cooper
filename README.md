android_device_samsung_cooper
==========================

Device configuration for Samsung cooper GT-S5830

Getting Started
---------------

To get started with Android for ARMv6/omniarmv6, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/omniarmv6/android.git -b android-4.4
    
Then to sync up:

    repo sync

Build your device:

    source build/envsetup.sh
    brunch cooper

Flash ZIP:

    out/target/product/cooper/omni-VERSION-DEVICENAME.zip


Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

For more information on this Github Organization and how it is structured,
please [read the wiki article](http://wiki.cyanogenmod.org/index.php/Github_Organization)

Disclaimer
--------

All of these device are not supported by omniarmv6 since they use the old Qualcomm
Snapdragon MSM7x27 chip, and hence cut off by the CyanogenMod team. This team (omniarmv6)
is in no way, shape or form affiliated by the CyanogenMod team and this project is not
endorsed or supported by the CyanogenMod team.

