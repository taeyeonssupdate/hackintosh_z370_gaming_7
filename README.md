# OpenCore on z370 i7-8700 rx580
<p align="center">
  <img src="./system.png" alt="System specs">
</p>

## Version
* macOS 10.15.6 Catalina
* OpenCore 0.5.9

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