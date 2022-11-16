# MSI-GS66-Stealth-OC-Hackintosh
### 好用请给我个star吧

## MSI GS66
| Specifications | Details |
|:-: |:-: |
| Processor | i7-10870H 8 Core  |
| RAM | 32GB DDR4 |
| SSD | 2xNVMe KC3000 2T + SN730 1T |
| Graphics Card | Intel UHD Graphics |
| eGPU | Nvidia GeForce RTX 3070 |
| Monitor | 15.6" Full HD 300Hz |
| Sound | Dynaudio Speakers 2W |
| Network Card | Intel AX210NGW |
| OS Version | Monterey 12.5 |

# Current Functionality

| Function | Performance |
|:-: |:-: |
| USB Patching | Excellent |
| Sleep | Excellent |
| Disable dGPU | Excellent |
| Enable iGPU | Excellent |
| Audio | Excellent |
| WiFi | Excellent |
| Ethernet | Excellent|
| Bluetooth | Good |
| Thunderbolt | Good |
| HDMI | Not work |
| CPU Optimisation | Excellent |
| Battery | Excellent |
| Brightness & Sound Keys | Excellent |
| General stability | Excellent |

#
#### To enter the Advanced BIOS
While in the BIOS, press F2, Left ALT, Right SHIFT, Right CTRL
Now you can verify that DVMT Pre-Allocated is set to 64MB and DVMT Total Gfx Mem is set to Max
Also, and most important, set CFG Lock to Disabled, to enable native PM (also you would probably get a KP without it, if using current version of the EFI)

#### IMPORTANT

Please generate a new SMBIOS (MacBookPro16,1 or MacBookPro16,4) as I deleted my serials. 
Use https://github.com/corpnewt/GenSMBIOS
