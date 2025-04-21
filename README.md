# OpenCore EFI for the Thinkpad X390

Not working:
- Bluetooth (Not needed)
- Ethernet (Not needed)
- I2C/SMBUS (Touchpad works via PS/2 instead)

Installation:
- [HfsPlus.efi](https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi) is needed for booting from HFS+ drives like the macOS installer.
- [IntelMausi.kext](https://github.com/acidanthera/IntelMausi) or some other kext needs to be installed in order to have working internet during the installation.
- [HeliPort.app](https://github.com/OpenIntelWireless/HeliPort) is required for getting Wi-Fi working after installation.
