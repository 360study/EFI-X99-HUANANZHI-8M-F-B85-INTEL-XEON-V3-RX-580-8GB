# Huananzhi 8M-F (B85 Chipset) + Intel Xeon E5-26XX v3 + RX 580 8Gb

**Latest working macOS**: 12.1
<br>
**Current OpenCore**: 0.7.7

## Complete hardware specs
- Intel Xeon E5-26XX v3 (HEDT Haswell)
- Huananzhi 8M-F (B85 Chipset)
- AMD RX 580 8 Gb (Polaris)
- Áudio Codec: Realtek ALC662
- Ethernet: Realtek 8111H Gigabit

## What works
- macOS Big Sur, macOS Catalina and macOS Monterey
- Audio
- HDMI/DP
- All USB ports
- Ethernet
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Correct USB Mapping :(

## Kexts used:
- AppleALC.kext
- CpuTscSync.kext
- Lilu.kext
- RealtekRTL8111.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBInjectAll.kext
- VirtualSMC.kext
- WhateverGreen.kext
- XHCI-unsupported.kext

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI Intel Haswell-E (HEDT)](https://github.com/luchina-gabriel/BASE-EFI-INTEL-HEDT-4THGEN-X99-HASWELL-E)

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
