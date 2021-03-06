# Lenovo Ideapad S145 Hackintosh

![Lenovo Ideapad S145 Hackintosh](/image.png)

## My specs

| Specs | Details |
|------------|-------------------------------|
| Model | Lenovo Ideapad S145 81S90003BR |
| OS | macOS Catalina 10.15.3 |
| CPU | Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz |
| RAM | 20 GB DDR4 2400MHz |
| iGPU | Iris Plus Graphics 655 (Fake GPU for HD 620) |
| WiFi | Wireless USB Adapter TL-WN725N V3 |

### Works

- [x] Intel Integrated Graphics
- [x] USB
- [x] Webcam
- [x] Brightness controls
- [x] Battery percentage
- [x] Sleep
- [x] TouchPad w/ Advanced Gestures
- [x] WiFi w/ USB Adapter
- [x] HDMI w/ Audio
- [x] Speakers
- [x] P2 Audio Jack w/ Microphone
- [x] Integrated Microphone
- [x] Apple Services (iCloud, Apple Music, Apple TV, others..)

### Doesn't work

- [ ] NVIDIA MX110 (disabled)
- [ ] SD Card Reader (haven't tested)
- [ ] Bluetooth (adapter needed)
- [ ] Airdrop + Handoff (haven't tested)

## Tools

- [Olarila](https://www.olarila.com/): Download macOS ISO
- [gibMacOS](https://github.com/corpnewt/gibMacOS): Download macOS Vanilla ISO
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS): Generate SMBIOS
- [ABNT2-Layout](https://github.com/lailsonbm/ABNT2-Layout): Brazilian ABNT2 Keyboard
- [MountEFI](https://github.com/corpnewt/MountEFI): EFI Partition Mounter
- [ProperTree](https://github.com/corpnewt/ProperTree): plist File Editor

## Guide

### BIOS Setup

- Set "Supervisor Password"
- Set "Password on Boot"
- Disable "Secure Boot"

### Setup

- Copy this EFI folder
- Generate your own SMBIOS
- (Optional) Install Brazilian ABNT2 Keyboard Support

## Thanks

Thanks to "MaLd0n" for his post on Olarila: https://www.olarila.com/topic/6874-olarila-hackbook-lenovo-ideapad-s145-8th-gen-mojave-catalina-big-sur-full-dsdt-patches-clover-and-opencore/