# LibreSDR - A Comprehensive Resource

Welcome to my LibreSDR repository! This is my collection of information, files, and tools related to the LibreSDR device. I've decided to compile everything I could find on here because it was quite a hassle to gather all the pieces. Hopefully, this repository can help others who are struggling with their devices.

## Introduction

Navigating through the scattered information about LibreSDR can be a pain. This repository aims to centralize that information, making it more accessible and comprehensible for everyone. Whether you're trying to flash firmware, recover from a brick, or just understand more about your device, you're in the right place.

## Contents

### Docs

In the `Docs` folder, you'll find:
- **Research Paper** that provides more detail than any of the seller pages. This should be your go-to document for a deep dive into the functionality and architecture of the LibreSDR.
- **How to Burn the Firmware to Flash**: Warning: Follow at your own risk, as I initially bricked my device during this process. If anyone has a more detailed and reliable method, please consider contributing.

### Firmware & Device Files

In the `Firmware&deviceFiles` folder, you'll find:
- **burn_flash files**: Referenced in our documentation on how to flash the firmware.
- **plutosdr-fw-v0.37-dirty**: Typically linked by sellers but was ineffective for me.
- **Working firmware**: This is the firmware that successfully worked(with the base clock).
- **Mystery-fw**: This firmware came pre-installed with my device and remains a mystery. I does allow DHCP to work. Note: The files from the only readable partitions I could access are mostly here; however, the files alone will not boot the device.
                   It is to large for Github (about 30 GB) ask me for the torent or download and I will get you a forensic image

### Tools

In the `Tools` folder, you'll find:
- **UPDATE.bat**: Referenced in our firmware flashing guide but was rather ineffective.
- **M2k drivers**: Necessary drivers for running and interfacing with the LibreSDR.
- **Digilent**: Additional tools related to the Digilent platforms.


### Contributing

Your contributions are highly appreciated! If you have:
- A more detailed and reliable way to flash the firmware.
- Any insights on what the DFU button actually does (it seemed non-functional in my experience).
- Any other tools, drivers, or useful information.

Please feel free to fork this repository, make your changes, and submit a pull request.

### Additional Resources

- **Forensic Image**: I have a 30 GB forensic image of the SD card that works with the mystery two partitions that I canot access. I can create a torrent link if there is interest. Please open an issue to request this.

## Issues

Encountered an issue or have a question? Check out the [Issues](https://github.com/yourusername/LibreSDR/issues) tab to see if it's been discussed, or feel free to open a new one.

Thank you for visiting this repository, and I hope it assists you in your LibreSDR journey!
