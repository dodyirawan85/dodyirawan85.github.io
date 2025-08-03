---
layout: post
title: "[August 2025] LineageOS 22.2 For Redmi Pad SE (xun)"
date: 2025-08-03 18:00:00 +0700
categories: custom rom
author: 'irawansalt'
---
![LineageOS Banner](/assets/images/banner/lineageos.jpeg)

{% include disclaimer.md %}

**DEVICES :** xun<br>
**BUILD DATE :** 03 August 2025<br>
**FIRMWARE :** OS2.0.2.0.VMUMIXM<br>
**TYPE :** Vanilla

**Changelogs**
<ol>
    <li>July security patch</li>
    <li>Update common blobs to july releases</li>
</ol>

**Prerequisites**
<ol>
    <li>Unlocked Bootloader</li>
</ol>

**Known Issues**
<ol>
    <li>Adaptive Brightness</li>
    <li>Screen recording (Use 3rd party app)</li>
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

2. Flash OS2.0.2.0.VMUMIXM Firmware
3. Reboot Recovery
4. Format Data
5. Flash Rom
6. Reboot Recovery (optional)
7. Flash GAPPS (optional)
8. Reboot system

**Screenshots**

![Lock Screen](/assets/images/screenshots/2025/August/03/lineageos_xun_1.png){: width="768"}{: height="480"}
![Home Screen](/assets/images/screenshots/2025/August/03/lineageos_xun_2.png){: width="768"}{: height="480"}
![About Phone](/assets/images/screenshots/2025/August/03/lineageos_xun_3.png){: width="768"}{: height="480"}

**Download**

[boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/03%20August%202025/boot.img/download)

[dtbo.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/03%20August%202025/dtbo.img/download)

[init_boot.img (for manual patch in magisk app)](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/03%20August%202025/init_boot.img/download)

[recovery.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/03%20August%202025/recovery.img/download)

[vendor_boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/03%20August%202025/vendor_boot.img/download)

[OS2.0.2.0.VMUMIXM Firmware](https://sourceforge.net/projects/irawansprojekt/files/xun/fw/fw_xun_global_xun_global-ota_full-OS2.0.2.0.VMUMIXM-user-15.0-d04012abfb.zip/download)

lineage-22.2-20250803_104737-UNOFFICIAL-xun.zip

[Link with ads to support me][alternate-link] | [Direct Link][direct-link]

**Thanks to**

1. boedhack99 for initial common tree and all xiaomi bengal / sm6225 devs
2. xmfirmwareupdater for firmware files

[direct-link]: https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/LineageOS/03%20August%202025/lineage-22.2-20250803_104737-UNOFFICIAL-xun.zip/download

[alternate-link]: https://sfl.gl/OpSmWZL
