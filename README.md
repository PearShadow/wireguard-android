# Android GUI for [WireGuard](https://www.wireguard.com/)

**[Download from the Play Store](https://play.google.com/store/apps/details?id=com.wireguard.android)**

This is an Android GUI for [WireGuard](https://www.wireguard.com/). It [opportunistically uses the kernel implementation](https://git.zx2c4.com/android_kernel_wireguard/about/), and falls back to using the non-root [userspace implementation](https://git.zx2c4.com/wireguard-go/about/).

## Building

```
$ git clone --recurse-submodules https://github.com/PearShadow/wireguard-android.git
$ cd wireguard-android
$ ./gradlew assembleRelease
```

macOS users may need [flock(1)](https://github.com/discoteq/flock).

## Modifications

- Added application to load on boot and enter the TV activity. 
- After successful connection on tunnel start intent to navigate to [com.example.nrg](https://github.com/PearShadow/nrg-android)