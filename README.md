# Clover EFI for Ryzen 2600X &amp; ROG B450I

## HW Builds

| Type                 | Name                                      | Instead |
| -------------------- | ----------------------------------------- | ------- |
| CPU                  | AMD Ryzen 5 2600X                         |         |
| MB                   | ROG STRIX B450-I GAMING                   |         |
| Audio                | S1220A （ALC1220）                        |         |
| GPU                  | Sapphire Radeon RX 580 8 GB （海外版）    |         |
| RAM                  | Teclast P70 RGB 16G DDR4 3000MHz (8G * 2) |         |
| Wireless & Bluetooth | Realtek 8822BE （unsolvable）             | DW1820A |
| WLAN                 | Intel® I211-AT                            |         |

## Functional

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] USB by [XLNC's script](https://forum.amd-osx.com/viewtopic.php?f=24&t=4986)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alc id = 7)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [ ] WIFI by [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) (brcmfx-country = #a)
- [x] Bluetooth by [BrcmPatchRAM](https://github.com/RehabMan/OS-X-BrcmPatchRAM) and [nickhx from osxlatitude](https://osxlatitude.com/forums/topic/11540-dw1820a-the-general-troubleshooting-thread/page/10/)
- [ ] iMessage / FaceTime / Airdrop / Handoff

## Issues

- Unknown processor in About This Mac (need to modify system files)
- Wrong ram speed display in About This Mac (shows half speed)
- No 32-bit support
- Can't run andriod emulator since android emulator only supports vt-x, but genymotion and virtualbox with amd-v support work well
