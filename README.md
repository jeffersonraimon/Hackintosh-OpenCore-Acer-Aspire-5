# Hackintosh-OpenCore-Acer-Aspire-5
Hackintosh made in 2021 with OpenCore running macOS Big Sur

## Specs
```
Model: Acer Aspire 5 A515-54-57EN

Processor: Intel Core i5 10210U (4 core, 8 Threat) 1.60Ghz - 4.2Ghz

Ram: 8 GB DDR4 

SSD M.2 NVMe: Kingston 256 GB (Zorin OS)
SSD 1: WDGreen 240Gb (macOS Big Sur)

Graphics: Intel UHD GraphicsG1

Audio codec: Realtek® ALC255 

Ethernet: Gigabit Ethernet

WiFi Card: Fenvi Chipset: Broadcom BCM94360NG

```
## BIOS Settings

### Disable

```
* Fast Boot
* Secure Boot
* Serial/COM Port
* Intel Platform Trust
* CSM
* Intel SGX
* Intel Platform Trust
* CFG Lock

```
### Enable

```
* VT-d
* Above 4G decoding
* Internal Graphics - Option: Enabled
* XHCI Hand-off
* OS type: Windows 8.1/10 UEFI Mode
* SATA Mode: AHCI  ( Hit F2 enter bios, select go to main tab of BIOS then hit Ctrl+S to enable hidden menu change Optane with RAID to AHCI and Save setting end exit.)
```

## IMPORTANT!!! - Change the SMBIOS

After download my EFI, plz change SMBIOS [How to do here](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo)

## Guide that I used

[Open Core Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

## Credits

To all stuff of OpenCore and the channel YouTube [Dicas do Mateus](https://www.youtube.com/channel/UCPCUdJ9cRior4FZ1TEz6qdA)
