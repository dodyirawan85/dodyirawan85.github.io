---
layout: post
title: "LineageOS 22.2 Unofficial For moto g45 5g (fogos)"
date: 2025-09-20 12:20:00 +0700
categories: custom rom
author: 'irawansalt'
---
![LineageOS Banner](/assets/images/banner/lineageos.jpeg)

{% include disclaimer.md %}

**DEVICES :** fogos<br>
**BUILD DATE :** 20 September 2025<br>
**FIRMWARE :** V1UGS35H.75-14-13-1<br>
**TYPE :** GAPPS

**Difference with official**
<ol>
    <li>Signed and user build</li>
    <li>Fixed volume keep at max even on lowest during voip call</li>
    <li>Fixed no sound issue when switching to speaker during voip call</li>
    <li>Fixed some mic issue during call</li>
    <li>Fixed crackling / noise sound on some games</li>
    <li>Fixed screen auto turned off issue during gaming session / on high temperature</li>
    <li>Include Dolby</li>
    <li>Include MotCamera</li>
</ol>

**Prerequisites**
<ol>
    <li>Unlocked Bootloader</li>
</ol>

**Known Issues**
<ol>
    <li>Auto HDR in MotCamera sometimes causing crashes, disable for workaround</li>
    <li>If you found more, report with proper logs</li>
</ol>

**Flashing Instruction Using AOSP Recovery**
1. Flash boot, dtbo, vendor_boot

    ```sh
    fastboot flash boot boot.img
    fastboot flash dtbo dtbo.img
    fastboot flash vendor_boot vendor_boot.img
    ```

2. Reboot recovery
3. Format Data
4. Flash Rom
5. Reboot system

**Screenshots**

![Lock Screen](/assets/images/screenshots/2025/September/20/lineageos_fogos_1.png){: width="240"}{: height="540"}
![Home Screen](/assets/images/screenshots/2025/September/20/lineageos_fogos_2.png){: width="240"}{: height="540"}
![About Phone](/assets/images/screenshots/2025/September/20/lineageos_fogos_3.png){: width="240"}{: height="540"}

**Download**

[boot.img](https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2015/LineageOS/20%20September%202025/boot.img/download)

[dtbo.img](https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2015/LineageOS/20%20September%202025/dtbo.img/download)

[vendor_boot.img](https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2015/LineageOS/20%20September%202025/vendor_boot.img/download)

lineage-22.2-20250920-UNOFFICIAL-fogos.zip

[Link with ads to support me][alternate-link] | [Direct Link][direct-link]

**Thanks to**

lineageos devs for base trees and all dev, tester who contribute in this rom

[direct-link]: https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2015/LineageOS/20%20September%202025/lineage-22.2-20250920-UNOFFICIAL-fogos.zip/download

[alternate-link]: https://sfl.gl/ioOuESJ
