# Rapid Fire Commander

Wired dashboard and OneROM bench utility for the Guition JC4880P443C_I_W/Y 4.3-inch ESP32-P4 display. The Windows kit includes Commander v0.11, Espressif esptool and a guided flash launcher.

The **SD Tune Selector** supports up to **64 `.BIN` files** from the root of a FAT32 microSD card. Only files that match the detected OneROM size can be selected.

1. Download the Windows kit from [Releases](https://github.com/RapidFire-001/rapid-fire-commander/releases).
2. Follow the [Windows flashing guide](WINDOWS.md) for the board check, backup, bootloader sequence and first boot.
3. Use the [menu and feature guide](HELP.md) for OneROM, SD cards, TunerPro, wideband and display settings.

This repository distributes compiled Commander firmware and documentation. See the [Commander firmware licence](FIRMWARE-LICENCE.md) for copyright and permitted use. The Commander project source and tune files are private. The kit includes separate notices and source for the third-party flasher.

The owner confirmed the v0.11 display boots on their P4. Treat tune writes and new board combinations as bench workflows and verify the result with OneROM disconnected from the ECU.
