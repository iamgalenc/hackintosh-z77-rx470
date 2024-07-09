# Hackintosh EFI for Z77 + RX 470 (Big Sur 11.7)
This repository contains the EFI folder and related files for creating a Hackintosh on a system with a Z77 Ivy Bridge chipset motherboard (Especially Gigabyte Z77-D3H) and an RX 470 4GB graphics card.

![Screen Shot 2024-07-09 at 09 21 04](https://github.com/iamgalenc/hackintosh-z77-rx470/assets/100140425/291e9a28-84e6-4466-b743-d1aa1973f8d3)

## Specification
| Part | Model |
| ---  | --- |
| CPU | Intel® Core™ i7-3770 (4 Cores, 8 Threads @3.90 GHz) |
| Motherboard | GIGABYTE GA-Z77-D3H (Rev. 1.0) |
| RAM | 24gb (2 x 8GB + 2 x 4GB) DDR3-1600MHz CL11 |
| DGPU | AMD RADEON Sapphire NITRO+ RX 470 OC 4GB 1206MHz |
| SSD | Adata SU650 120GB Sata SSD |
| AUDIO | VIA VT2021 |

## What Doesn't Work
- Airdrop/Handoff/Bluetooth : No Wi-Fi module in my PC (especially BCM94360CS2).
- 100Hz Refresh Rate : May need to reconfigure to make it work.

## Post-Installation Tasks
- Force RGB for >60hz monitor.
- Change audio layout : Set to 0x100100, layout 5, 7, 9, 3 (VT2021).
- Change graphic card fan curves : Use [saudor](https://www.youtube.com/@saudor) tutorial in the credits below.

## Credits
- [Acidanthera](https://github.com/acidanthera) for OpenCore and essential kexts.
- [Dortania](https://dortania.github.io/) for comprehensive Hackintosh guides.
- [Olarila](https://www.olarila.com/) for MacOS Big Sur offline installer.
- [MAKYT](https://www.youtube.com/watch?v=cDNvpYGIl_4&t=1s) for force RGB Patch.
- [saudor](https://www.youtube.com/watch?v=NNg5ahTh8UE&t=120s) for changing fan curves in AMD Polaris graphic card.
- All contributors to the Hackintosh community.
