# NEC-VK23VB-T-Hackintosh
## Overview
NEC-VK23VB-T is a laptop computer manufactured by NEC in Japan.
NEC has partnered with Lenovo for the Laptop division, so this laptop is compatible with the Lenovo X260, T460.
Therefore, I was able to realize many functions by applying the following three DSDT patches [tluck/Lenovo-T460-Clover](https://github.com/tluck/Lenovo-T460-Clover).

- 1_led_blink.txt　　　（Blinking LED during sleep and lighting during wakeup ）
- 2_IGBE_PRW.txt　　（Wake up from sleep with power button ）
- 4_battery_fan.txt　　（Patches for batteries, fans, etc. ）

The detailed log of how to make it is below.
[Summary: NEC VK23VB-T (VK23LBZDT) Hackintosh, i3-6100U, 16GB, SSD 1TB, Windows10Pro, Big Sur Dualboot (Clover & OpenCore) about 27,000 yen](https://mifmif.mydns.jp/alpha/?p=1629)

## ~Monterey
This laptop computer works as Mac Book Pro 13.1 up to macOS Monterey.

## Ventura(Developers Beta)
This laptop computer works as Mac Book Pro 14.1 up to macOS Monterey.
Since it uses the function of WhatEverGreen that disguises Skylake as Kabylake, it cannot coexist with the past OS.
If you want them to coexist, you have to use a preselector like rEFInd.
