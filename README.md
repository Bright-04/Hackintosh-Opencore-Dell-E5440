# Hackintosh OpenCore EFI for Dell E5440

This repository contains the EFI files for running macOS Monterey on a Dell E5440 laptop using OpenCore.

## Current Status

- macOS Monterey successfully installed
- Not fully tested - use at your own risk

## Hardware Specifications

- Model: Dell Latitude E5440
- CPU: Intel® Core™ i5-4200U
- GPU: Intel HD Graphics 4400 (integrated, no dedicated GPU)

## What Works
- **USB**: All USB 2.0 and 3.0 ports work flawlessly.
- **Audio**: Works with internal speakers and integrated microphone.
- **Sleep**: Sleep functionality works as expected.
- **Ethernet**: Wired Ethernet connection is fully functional.
- **Touchpad & Keyboard**: Both touchpad and keyboard are working seamlessly.
- **Webcam**: The built-in webcam is operational.
- **BD PROCHOT**: Fixed using .efi driver at boot.
- To be added

## Known Issues
- Display: No brightness control
- Bluetooth: Not working, to be fixed
- Wifi: Same as Bluetooth. (Currently using Ethernet)
- To be added

## Disclaimer

This EFI is provided as-is.  Always backup your data before attempting to install or update a Hackintosh system.

## Contributing

Feel free to open issues or pull requests if you have improvements or fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- **Dortania's OpenCore Guide**: A comprehensive resource that provides detailed instructions and best practices for setting up and configuring OpenCore for Hackintosh systems. [Dortania OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)

- **GenSMBIOS**: A tool that helps generate SMBIOS information for Hackintosh setups, ensuring proper identification of your system. [GenSMBIOS GitHub Repository](https://github.com/corpnewt/GenSMBIOS)

- **OpenCorePkg**: The core package of the OpenCore bootloader, which serves as the foundation for this Hackintosh setup. [OpenCorePkg GitHub Repository](https://github.com/acidanthera/OpenCorePkg)

- **ProperTree**: A cross-platform GUI plist editor that simplifies the editing of configuration files necessary for OpenCore. [ProperTree GitHub Repository](https://github.com/corpnewt/ProperTree)

- **Similar GitHub Repositories**: Special thanks to other contributors in the Hackintosh community, such as [axemre/OpenCore-Dell-Latitude-E5440](https://github.com/axemre/OpenCore-Dell-Latitude-E5440), which provided valuable insights and configurations.
