# 🌐 Opencore B460M Bazooka + Comet Lake + iGPU 
Opencore EFI configuration for MacOs Sonoma on the MSI MAG B460M BAZOOKA motherboard, using Intel I7-10700K (Comet Lake) processor, and iGPU Intel Graphics UHD 630

[**DOWNLOAD THE EFI FOLDER**](https://github.com/fran1215/OC-B460M-I710700K-UHD630/releases/download/0.0.1/EFI.zip)

![Resulting configuration](/assets/ConfigSonoma.png)

# ⚙️ Configuration
- **Motherboard**: [MSI MAG B460M BAZOOKA](https://www.msi.com/Motherboard/MAG-B460M-BAZOOKA)
- **Processor**: [Intel Core I7-10700K (Comet Lake)](https://www.intel.com/content/www/us/en/products/sku/199335/intel-core-i710700k-processor-16m-cache-up-to-5-10-ghz/specifications.html)
- **RAM**: [Kingston Hyperx Fury 16 GB (2 x 8 GB) 2933 MHz DDR4](https://www.kingston.com/en/memory/search/discontinuedmodels?partid=HX432C16FB3/8)
- **GPU**: Integrated GPU Intel UHD Graphics 630
- **SSD (External)**: [Sandisk Portable SSD 480GB](https://www.westerndigital.com/products/portable-drives/sandisk-usb-3-2-ssd#SDSSDE30-1T00-G26)
- **Ethernet**: Realtek 8111

# 🧑🏻‍💻 OpenCore + macOS Sonoma
## Opencore 0.9.5 Stable
- [**Opencore 0.9.5**](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.5)
- [**Instalation Guide**](https://dortania.github.io/OpenCore-Install-Guide/)

## macOS Sonoma 14.0
- [**macOs Sonoma**](https://www.apple.com/macos/sonoma/)

# ✅ What's working?
Basically everything is working, except for the dGPU (Gigabyte Geforce RTX 3060Ti) since Opencore doesn't support Nvidia RTX GPUs. Bluetooth and Wi-Fi are not working in this configuration since my desktop doesn't have a card for these, nor I have a dongle. DRM also doesn't work, but you can use other browsers to use video streaming platforms.


