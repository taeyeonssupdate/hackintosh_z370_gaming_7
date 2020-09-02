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

https://www.tonymacx86.com/threads/success-ga-z370-aorus-gaming-7-i7-8700k-rx5700xt-oc.299852/

https://www.tonymacx86.com/threads/amd-radeon-performance-enhanced-ssdt.296555/