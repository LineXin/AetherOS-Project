# AetherOS-Project
Manifest of AetherOS Project

Welcome to our project! (by AetherOS Developers)

# How to build ROM?

First, install Ubuntu/Debian (or build in server) and enter this on terminal:
```bash
repo init -u [https://github.com/LineXin/AetherOS-Project.git](https://github.com/LineXin/AetherOS-Project.git) -b main
```
After that:
```repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags```
