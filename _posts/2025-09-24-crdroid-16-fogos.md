---
layout: post
title: "crDroid 16 Unofficial For moto g45 5g (fogos)"
date: 2025-09-24 08:55:00 +0700
categories: custom rom
author: 'irawansalt'
---
![crDroid Banner](/assets/images/banner/crdroid.jpg)

{% include disclaimer.md %}

**DEVICES :** fogos<br>
**BUILD DATE :** 24 September 2025<br>
**FIRMWARE :** V1UGS35H.75-14-13-1<br>
**TYPE :** Vanilla

**Changelogs**
<ol>
    <li>Initial build</li>
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
5. Reboot recovery (optional)
6. Flash GAPPS (optional)
7. Reboot system

**Screenshots**

![Lock Screen](/assets/images/screenshots/2025/September/24/crdroid_fogos_1.png){: width="240"}{: height="540"}
![Home Screen](/assets/images/screenshots/2025/September/24/crdroid_fogos_2.png){: width="240"}{: height="540"}
![About Phone](/assets/images/screenshots/2025/September/24/crdroid_fogos_3.png){: width="240"}{: height="540"}

**Download**

[boot.img](https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2016/crDroid/24%20September%202025/boot.img/download)

[dtbo.img](https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2016/crDroid/24%20September%202025/dtbo.img/download)

[vendor_boot.img](https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2016/crDroid/24%20September%202025/vendor_boot.img/download)

crDroidAndroid-16.0-20250924-fogos-v12.1.zip

[Link with ads to support me][alternate-link] | [Direct Link][direct-link] or [Mirror][mirror]

**Thanks to**

lineageos devs for base trees and all dev, tester who contribute in this rom

[direct-link]: https://sourceforge.net/projects/irawansprojekt/files/fogos/Android%2016/crDroid/24%20September%202025/crDroidAndroid-16.0-20250924-fogos-v12.1.zip/download

[alternate-link]: https://sfl.gl/00YDO

[mirror]: https://pixeldrain.com/u/2QaF4BHo
