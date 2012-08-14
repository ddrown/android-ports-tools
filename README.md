Android Ports tools
===================

these scripts make it easier to port unix programs to android using android-ndk from google


To Setup a build environment:
-----------------------------

* Start with a linux machine
* Create a ~/droid and a ~/tmp directory
* Put this repo under ~/droid/bin
* create the directories ~/droid/lib and ~/droid/include
* Put the Android NDK under ~/droid/android-ndk (or use a symlink). Verify you have the directories ~/droid/android-ndk/platforms/android-8/arch-arm/usr/include/ and ~/droid/android-ndk/toolchains/arm-linux-androideabi-4.6/prebuilt/linux-x86/bin/
* put ~/droid/bin/ into your path
