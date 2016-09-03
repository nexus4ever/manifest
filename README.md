The neXus4ever Project
=====================

Getting Started
---------------

To build neXus4ever from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/nexus4ever/manifest.git -b n-7.0

Then to use the mako sources, use this command:

	mkdir .repo/local_manifests && cp .repo/manifests/local_manifests/roomservice.xml .repo/local_manifests

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka mako
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "userdebug" is default

Enjoy, Stick around for a while AOSP Building is Fun!!!

[@spezi77](http://forum.xda-developers.com/member.php?u=5091819) on XDA
[@Funny-Bunny](http://forum.xda-developers.com/member.php?u=5796730) on XDA


Big thanks to the [PureNexusProject] (https://github.com/PureNexusProject) Source and Reference code

