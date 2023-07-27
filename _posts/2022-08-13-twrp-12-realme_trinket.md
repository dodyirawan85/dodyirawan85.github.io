---
layout: post
title: "TeamWin Recovery Project 3.6.2 For Realme Trinket Devices"
date: 2022-08-13 12:46:00 +0700
categories: custom recovery
author: 'irawansalt'
---
![TWRP Banner](/assets/images/banner/twrp.jpeg)

{% include disclaimer.md %}

**DEVICES :** 5, 5i, 5s, 5 NFC, 5 Vietnam<br>
**BUILD DATE :** 13 August 2022<br>
**FIRMWARE :** RealmeUI

**Changelogs**
<ol>
    <li>Initial Build Based On Android 12 Source</li>
    <li>Fixed decryption in Android 12</li>
    <li>Added RMX1919 (5 Vietnam) to device list</li>
</ol>

**Known Issue**
<ol>
    <li>False filesystem detection (userdata keeps detecting as ext4 while the actual filesystem is f2fs)</li>
    <li>You Tell Me</li>
</ol>

**Prerequisites**
<ol>
    <li>Basic understanding to operate fastboot command</li>
    <li>Unlocked Bootloader</li>
    <li>Platform Tools And adb fastboot driver installed</li>
</ol>

**Flashing Instruction**
<ul>
    <li>Go to fastboot</li>
    <li>Connect your device to the pc</li>
    <li>Run {% highlight bash %}fastboot flash recovery TWRP-3.6.2-12-20220812-realme_trinket-dodyirawan85.img {% endhighlight %}
    </li>
    <li>Reboot to recovery</li>
</ul>

**Download**

[TWRP-3.6.2-12-20220812-realme_trinket-dodyirawan85.img][twrp-links]


[twrp-links]: https://github.com/realme-trinket-organization/releases/releases/download/TWRP-3.6.2-12-20220812-realme_trinket-dodyirawan85/TWRP-3.6.2-12-20220812-realme_trinket-dodyirawan85.img
