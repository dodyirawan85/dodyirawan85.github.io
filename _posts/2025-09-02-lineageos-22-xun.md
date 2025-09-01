---
layout: post
title: "[September 2025] LineageOS 22.2 For Redmi Pad SE (xun)"
date: 2025-09-02 00:22:00 +0700
categories: custom rom
author: 'irawansalt'
---
![LineageOS Banner](/assets/images/banner/lineageos.jpeg)

{% include disclaimer.md %}

**DEVICES :** xun<br>
**BUILD DATE :** 01 September 2025<br>
**FIRMWARE :** OS2.0.204.0.VMUMIXM<br>
**TYPE :** Vanilla

**Changelogs**
<ol>
    <li>Auggust security patch</li>
    <li>Fixes built-in screenrecorder</li>
    <li>Revert to older brightness behaviour</li>
    <li>Enable wifi display (untested, report if buggy)</li>
    <li>Include latest device firmware OS2.0.204.0.VMUMIXM</li>
    <li>And more</li>
</ol>

**Prerequisites**
<ol>
    <li>Unlocked Bootloader</li>
</ol>

**Known Issues**
<ol>
    <li>Adaptive Brightness</li>
    <li>If found more, report with proper logs</li>
</ol>

**Flashing Instruction Using AOSP Recovery**
1. Flash boot, dtbo, recovery and vendor_boot

    ```sh
    fastboot flash boot boot.img
    fastboot flash dtbo dtbo.img
    fastboot flash recovery recovery.img
    fastboot flash vendor_boot vendor_boot.img
    fastboot reboot recovery
    ```

2. Format Data
3. Flash Rom
4. Reboot Recovery (optional)
5. Flash GAPPS (optional)
6. Reboot system

**Screenshots**

![Lock Screen](/assets/images/screenshots/2025/September/02/lineageos_xun_1.png){: width="768"}{: height="480"}
![Home Screen](/assets/images/screenshots/2025/September/02/lineageos_xun_2.png){: width="768"}{: height="480"}
![About Phone](/assets/images/screenshots/2025/September/02/lineageos_xun_3.png){: width="768"}{: height="480"}

**Download**

[boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/01%20September%202025/boot.img/download)

[dtbo.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/01%20September%202025/dtbo.img/download)

[init_boot.img (for manual patch in magisk app)](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/01%20September%202025/init_boot.img/download)

[recovery.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/01%20September%202025/recovery.img/download)

[vendor_boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/01%20September%202025/vendor_boot.img/download)

lineage-22.2-20250901_164402-UNOFFICIAL-xun.zip

[Link with ads to support me][alternate-link] | [Direct Link][direct-link]

**Thanks to**

1. boedhack99 for initial common tree and all xiaomi bengal / sm6225 devs
2. xmfirmwareupdater for firmware files

[direct-link]: https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/01%20September%202025/lineage-22.2-20250901_164402-UNOFFICIAL-xun.zip/download

[alternate-link]: https://sfl.gl/knLr
