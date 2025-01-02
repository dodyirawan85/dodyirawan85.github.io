---
layout: post
title: "LineageOS 21.0 For Xiaomi Redmi Pad SE (xun)"
date: 2025-01-02 07:00:00 +0700
categories: custom rom
author: 'irawansalt'
---
![LineageOS Banner](/assets/images/banner/lineageos.jpeg)

{% include disclaimer.md %}

**DEVICES :** xun<br>
**BUILD DATE :** 02 January 2025<br>
**FIRMWARE :** OS1.0.7.0.UMUMIXM<br>
**TYPE :** Vanilla

**Changelogs**
<ol>
    <li>Initial OSS vendor build</li>
    <li>Fix device not sleep while closing flip cover</li>
    <li>Fix booting issue on newer batch</li>
    <li>Add charging control</li>
    <li>And more</li>
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

2. Flash OS1.0.7.0.UMUMIXM Firmware
3. Reboot Recovery
4. Format Data
5. Flash Rom
6. Reboot Recovery (optional)
7. Flash GAPPS (optional)
8. Reboot system

**Screenshots**

![Lock Screen](/assets/images/screenshots/2025/January/02/lineageos_xun_1.png){: width="768"}{: height="480"}
![Home Screen](/assets/images/screenshots/2025/January/02/lineageos_xun_2.png){: width="768"}{: height="480"}
![Status Bar](/assets/images/screenshots/2025/January/02/lineageos_xun_3.png){: width="768"}{: height="480"}
![About Phone](/assets/images/screenshots/2025/January/02/lineageos_xun_4.png){: width="768"}{: height="480"}

**Download**

[boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android-14/LineageOS/02%20January%202025/boot.img/download)

[dtbo.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android-14/LineageOS/02%20January%202025/dtbo.img/download)

[recovery.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android-14/LineageOS/02%20January%202025/recovery.img/download)

[vendor_boot.img](https://sourceforge.net/projects/irawansprojekt/files/xun/Android-14/LineageOS/02%20January%202025/vendor_boot.img/download)

[OS1.0.7.0.UMUMIXM Firmware](https://sourceforge.net/projects/irawansprojekt/files/xun/fw/fw_xun_miui_XUNGlobal_OS1.0.7.0.UMUMIXM_05fc1ffc2b_14.0.zip/download)

lineage-21.0-20250102-UNOFFICIAL-xun.zip

[Link with ads to support me][alternate-link] | [Direct Link][direct-link]

**Thanks to**

1. boedhack99 for initial common tree and all xiaomi bengal / sm6225 devs
2. xmfirmwareupdater for firmware files
3. all testers

[direct-link]: https://sourceforge.net/projects/irawansprojekt/files/xun/Android-14/LineageOS/02%20January%202025/lineage-21.0-20250102-UNOFFICIAL-xun.zip/download

[alternate-link]: https://sfl.gl/1BoH1
