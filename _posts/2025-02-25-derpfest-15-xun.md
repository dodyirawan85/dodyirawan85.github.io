---
layout: post
title: "DerpFest 15 For Redmi Pad SE (xun)"
date: 2025-02-25 12:53:00 +0000
categories: custom rom
author: 'irawansalt'
---
![DerpFest Banner](/assets/images/banner/derpfest.png)

{% include disclaimer.md %}

**DEVICES :** xun<br>
**BUILD DATE :** 25 February 2025<br>
**FIRMWARE :** OS2.0.1.0.VMUMIXM<br>
**TYPE :** GAPPS

**Changelogs**
<ol>
    <li>Initial Build</li>
</ol>

**Prerequisites**
<ol>
    <li>Unlocked Bootloader</li>
</ol>

**Known Issues**
<ol>
    <li>Adaptive Brightness</li>
    <li>Screen recording (Use 3rd party app)</li>
    <li>Offline charging</li>
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

2. Flash OS2.0.1.0.VMUMIXM Firmware
3. Reboot Recovery
4. Format Data
5. Flash Rom
8. Reboot system

**Screenshots**

![Lock Screen](/assets/images/screenshots/2025/February/25/derpfest_xun_1.png){: width="768"}{: height="480"}
![Home Screen](/assets/images/screenshots/2025/February/25/derpfest_xun_2.png){: width="768"}{: height="480"}
![About Phone](/assets/images/screenshots/2025/February/25/derpfest_xun_3.png){: width="768"}{: height="480"}

**Download**

[boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/DerpFest/25%20February%202025/boot.img/download)

[dtbo.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/DerpFest/25%20February%202025/dtbo.img/download)

[init_boot.img for patch image in magisk](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/YAAP/24%20February%202025/init_boot.img/download)

[recovery.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/DerpFest/25%20February%202025/recovery.img/download)

[vendor_boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/DerpFest/25%20February%202025/vendor_boot.img/download)

[OS2.0.1.0.VMUMIXM Firmware](https://sourceforge.net/projects/irawansprojekt/files/xun/fw/fw_xun_global_xun_global-ota_full-OS2.0.1.0.VMUMIXM-user-15.0-2de2c70e8d.zip/download)

DerpFest-15.1-Community-Stable-xun-20250225-1254.zip

[Link with ads to support me][alternate-link] | [Direct Link][direct-link]

**Thanks to**

1. boedhack99 for initial common tree and all xiaomi bengal / sm6225 devs
2. xmfirmwareupdater for firmware files
3. all testers

[direct-link]: https://sourceforge.net/projects/irawansprojekt/files/xun/Android%2015/DerpFest/25%20February%202025/DerpFest-15.1-Community-Stable-xun-20250225-1254.zip/download

[alternate-link]: https://sfl.gl/L1huH
