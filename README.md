BitOSP
======

Getting Started
---------------

To initialize this repository:

	repo init -u https://github.com/BitOSP/manifest.git -b mm

To sync source:

	repo sync

After syncing you can use these commands to build:

	. build/envsetup.sh
	brunch <DEVICE_NAME> [BUILD_TYPE]

Notes:

- BUILD_TYPE must be one of: user, userdebug, eng
- If no BUILD_TYPE is specified then "userdebug" is used.
    

More info:

- Using [Git and Repo](http://source.android.com/source/using-repo.html).
