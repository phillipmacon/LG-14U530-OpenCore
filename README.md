# LG 14U530 Hackintosh

## Before Install...
- You have to choose "CFGLock.efi" in boot menu.

## Specification
| Component | Details |
| - | - |
| CPU | Intel Core i5-4200U |
| iGPU | Intel HD Graphics 4400 |
| dGPU | Nvidia GeForce GT 720M |
| RAM | Apple HMT451S6BFR8A-PB * 2 |
| LCD | LP140WF1-SPJ1 (LGD0406) |
| WLAN | Intel Dual Band AC 7260 |
| Audio | Realtek ALC282 (Layout ID: 86) |
| BIOS (UEFI) | 14U530F9 (04/17/2014) |

## Reported Issues
- Wi-Fi doesn't work after waking up from sleep. (sometimes)
- Bluetooth has short range because of AirportItlwm.
- VGA works, but unplugging detection is broken.
- Touchpad pointing speed is slightly faster after boot.
- Booting is slower than Windows. (SSD Trim Problem?)

## It does not work
- dGPU
- SD Card Reader (RTS5129)
- Windows-only Function Keys
- Hibernation (Mode 25)