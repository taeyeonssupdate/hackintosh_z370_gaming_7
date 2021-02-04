# Hackintosh with Opnecore (z370 i7-8700k rx580 8G 32gb ram)
<p align="center">
  <img src="./system.png" alt="System specs">
</p>

## Version
* macOS 11.2 Catalina
* OpenCore 0.6.6
### other version
<a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/4a7d29a"><img src="https://is4-ssl.mzstatic.com/image/thumb/Purple124/v4/09/59/3d/09593d0e-188a-77eb-4c38-ca40bedd5cff/ProductPageIcon.png/460x0w.webp" height="32px"/></a>[macOS 11.2](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/4a7d29a)
* [OpenCore 0.6.6](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/4a7d29a)


<a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/908baab"><img src="https://is4-ssl.mzstatic.com/image/thumb/Purple124/v4/09/59/3d/09593d0e-188a-77eb-4c38-ca40bedd5cff/ProductPageIcon.png/460x0w.webp" height="32px"/></a>[macOS 11.0.1](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/908baab)
* [OpenCore 0.6.5](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/908baab)
* [OpenCore 0.6.3](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/a7e27f6)

<a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/2af5c9"><img src="https://km.support.apple.com/resources/sites/APPLE/content/live/IMAGES/0/IM935/en_US/macos-catalina-roundel-240.png" height="32px"/></a>[macOS 10.15.7](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/2af5c9)
* [OpenCore 0.6.3](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/2af5c9d)

<a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/ba1036b"><img src="https://km.support.apple.com/resources/sites/APPLE/content/live/IMAGES/0/IM935/en_US/macos-catalina-roundel-240.png" height="32px"/></a>[macOS 10.15.6](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/ba1036b)
* [OpenCore 0.6.2](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/ba1036b)
* [OpenCore 0.6.1](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/66c2799)
## Hardware

* Intel Core i7-8700K Coffee Lake
* Gigabyte Z370 AORUS Gaming 7
* Gigabyte Radeon RX 580 GAMING 8G
* 2x16GB HyperX FURY DDR4 3466Mhz HX434C17FB4/16
* SSD CRUCIAL MX500 CT500MX500SSD1
* PCI-e Broadcom BCM4360 WiFi ac + USB Bluetooth 4.0

## ACPI
* SSDT-AWAC.aml
* SSDT-EC-USBX.aml
* SSDT-PLUG.aml
* SSDT-RX580.aml

## Kexts
* AirportBrcmFixup.kext
* AppleALC.kext
* AtherosE2200Ethernet.kext
* IntelMausi.kext
* Lilu.kext
* SMCProcessor.kext
* SMCSuperIO.kext
* USBPorts.kext
* VirtualSMC.kext
* WhateverGreen.kext
* DAGPM.kext

## Drivers
* AudioDxe.efi
* HfsPlus.efi
* OpenCanopy.efi
* OpenRuntime.efi

# ALAC1220 (顯示由上而下)
## 1 
  Linein k
  Linein j
  耳機 n 前板插入斷聲音 還是耳機
## 2
  Linein o
  Linein m
  耳機 n
  前板 內建
## 7
  Linein j
  Linein k
  耳機 n 沒聲音
  前板 內建
## 11
  Linein j
  Linein  k
  耳機 n 沒聲音
  前板 內建
## 16
  Linein k
  Linein j
  耳機 前板
  內建 n
## 27
  Linein j
  Linein k
  Linein 沒聲音
  (n 沒聲音)
  內建 前板
## 28
  Linein j
  Linein k
  內建 n (需手動切換)
  內建 前板 (需手動切換)
## 29
  Linein j
  Linein k
  耳機 n 沒聲音
  內建 前板



## setup
1. https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide
2. reboot select reset nvram
3. boot from macOS

https://www.tonymacx86.com/threads/success-ga-z370-aorus-gaming-7-i7-8700k-rx5700xt-oc.299852/

https://www.tonymacx86.com/threads/amd-radeon-performance-enhanced-ssdt.296555/