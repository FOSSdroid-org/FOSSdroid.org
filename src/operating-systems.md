# Operating Systems (ROMs)

Usually referred as "Custom ROMs", these are Android-based operating systems (OS), forked from the Android Open Source Project (AOSP), maintained independently. When compared to the pre-installed factory operating systems that come with the devices, these Android distributions does provide enhanced privacy and depends on none or much less propertiary code.

## Active distributions

### LineageOS

Continuing the legacy of the CyanogenMod project that started development in 2009, LineageOS is one of the most widely used Android distribution. It supports a very wide range of Android devices on the market. LineageOS comes with several unique features backed in on top of AOSP, such as system profiles, privacy guard, more screen lock options, protected apps and more.

[LineageOS website](https://lineageos.org/)

### GrapheneOS

GrapheneOS is a hardened private and secure Android distribution from bottom up, it brings various measurements and fixes to prevent vulnerabilities and exploits that may arise from AOSP base, and provides specialized options to the user to maximise data security and privacy, such as; isolated memory for per-app, USB-C port security, auto-reboot, sandboxed Google Play, controlling network permission and more. It only supports devices that meet GrapheneOS standards, specifically Google Pixel devices.

[GrapheneOS website](https://grapheneos.org/)

## Discontinued distributions

### DivestOS

DivestOS was a soft-fork of LineageOS aimed to increase security and privacy with its support for end-of-life devices. Being derivated from LineageOS, it supported devices that had been supported by LineageOS. It also had adopted several privacy & security features from GrapheneOS, and was allowing re-locking the bootloader on some devices. As of December 2024, DivestOS was discontinued and its website were taken down.

## Google services

AOSP itself doesn't actually require Google apps to function properly, so Google apps are an optional component for the Android system, but device manufacturers (OEMs) usually choose to bundle [Google Mobile Services (GMS)](https://en.wikipedia.org/wiki/Google_Mobile_Services) with their OSes since many users find Google apps useful for getting the most out of the Android ecosystem at the cost of privacy.

Since these apps are proprietary and invades data privacy (because of Google Play Services having priveleged access to the system), most custom Android distributions simply not choose to pre-install Google apps, so users whose would like to have Google services on their devices can optionally download & install Google apps as they wish.

Most third-party applications depend the existence Google Play Services to access APIs provided by it (such as sending & receiving push notifications sent through Google servers), therefore these applications may not function properly or may not work at all without it.

### microG

[microG](https://github.com/microg/GmsCore) is an free (as-in freedom) implementation of Google Play Services, serving as a replacement for it by implementing same Google APIs to be provided to the other apps; so apps can continue working as they do with Google Play Services installed. This means that microG needs to connect to Google servers to provide same APIs as in Google Play Services anyway, but unlike Google Play Services, microG is open source and uses less identifiers so it may be a more preferable solution in terms of the privacy.

## See also

[Wikipedia: List of custom Android distributions](https://en.wikipedia.org/wiki/List_of_custom_Android_distributions)