# Hackintosh with Opnecore (z370 i7-8700k 32gb ram) 
# ~~rx580 8G deleted~~

<p align="center">
  <img src="./system.png" alt="System specs">
</p>

## Version

- <a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/f8c67bd51c3194c2c665454cf42c2ce00a7ff18e"><img src="https://i.pcmag.com/imagery/reviews/04iuiyBZ61YPzdVS4GfRYKM-29.fit_scale.size_760x427.v1666629922.png" height="32px"/></a>[macOS 13.0 Ventura](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/f8c67bd51c3194c2c665454cf42c2ce00a7ff18e)

- <a href="https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/f8c67bd51c3194c2c665454cf42c2ce00a7ff18e"><img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/></a>[OpenCore 0.8.5](https://github.com/taeyeonssupdate/OpenCore-Z370-Gaming-7-i8-8700k-rx580-8G/tree/f8c67bd51c3194c2c665454cf42c2ce00a7ff18e)

## setup

- [How to decide](https://dortania.github.io/OpenCore-Install-Guide/extras/smbios-support.html#how-to-decide)
- reboot select reset nvram
- boot from macOS

## source

- https://www.tonymacx86.com/threads/success-ga-z370-aorus-gaming-7-i7-8700k-rx5700xt-oc.299852/
- https://www.tonymacx86.com/threads/amd-radeon-performance-enhanced-ssdt.296555/

## Hardware

- Intel Core i7-8700K Coffee Lake
- Gigabyte Z370 AORUS Gaming 7
- ~~Gigabyte Radeon RX 580 GAMING 8G~~
- 2x16GB HyperX FURY DDR4 3466Mhz HX434C17FB4/16
- SSD CRUCIAL MX500 CT500MX500SSD1
- PCI-e Broadcom BCM4360 WiFi ac + USB Bluetooth 4.2

## ACPI

- SSDT-AWAC.aml
- SSDT-EC-USBX.aml
- SSDT-PLUG.aml
- ~~SSDT-RX580.aml~~
- SSDT-UIAC.aml

## Kexts

- AirportBrcmFixup.kext
- AppleALC.kext
- AppleALCU.kext
- AtherosE2200Ethernet.kext
- DAGPM.kext
- IntelMausi.kext
- IntelSnowMausi.kext
- Lilu.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBPorts.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Drivers

- AudioDxe.efi
- ext4_x64.efi
- OpenHfsPlus.efi
- OpenCanopy.efi
- OpenLinuxBoot.efi
- OpenRuntime.efi

## Tools

- OpenShell.efi

## BIOS (Download from folder restore in BIOS)

- F15b (BIOS babckup)
- Profiles 0.7 (Profiles backup)
