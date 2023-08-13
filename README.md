## Ryzentosh-EFI
This repository contains backup EFI data for my Ryzentosh PC (macOS as main OS) running macOS Ventura and OpenCore . This is not a documentation on how to re-use this EFI for personal use. If attempted, please use at your own risk.

<div align="center">
<img width="200" src="./assets/Screenshot 2023-08-13 at 19.09.33.png"></img>
</div>


## Hardware
- Gigabyte Aorus x570 Motherboard
- AMD Radeon RX 6800XT 16GB
- AMD Ryzen 5 5600X
- 32 GB 2666 MHz DDR4
- Pixio PX277P Monitor

## Works/Doesn't work

### What works
- Almost everything including Apple continuity.
- DRM

### What doesn't work
- Sidecar
- iPhone hotspot via USB (Can only connect the phone to access storage etc)

## OpenCore Internals
### ACPI
- SSDT-EC-USBX-DESKTOP.aml

### Drivers
- OpenCanopy.efi
- OpenHfsPlus.efi
- OpenRuntime.efi

### Kexts
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleIGB.kext
- AppleMCEReporterDisabler.kext
- CtlnaAHCIPort.kext
- Lilu.kext
- NVMeFix.kext
- RadeonSensor.kext
- RestrictEvents.kext
- SMCAMDProcessor.kext
- SMCRadeonGPU.kext
- VirtualSMC.kext
- WhateverGreen.kext


### Tools
- CleanNvram.efi
- OpenShell.efi

