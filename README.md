# AetherOS-Project
Manifest of AetherOS Project

Welcome to our project! (by AetherOS Developers)

# How to build ROM?

First, install Ubuntu/Debian (or build in server) and enter this on terminal:
```bash
repo init -u [https://github.com/LineXin/AetherOS-Project.git] -b main
```
After that:
```repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags```
# Building tiiime!!
After sync, let's begin to build a ROM!
Enter this on terminal:
```bash
. build/envsetup.sh
lunch aether_[codename]-userdebug
m aether
```
Now, your build will start!
Thanks for your attention!
