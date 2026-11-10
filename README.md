# Rapid Fire Commander

Wired dashboard and OneROM bench utility for the Guition JC4880P443C_I_W/Y 4.3-inch ESP32-P4 display. The Windows kit includes Commander v0.13, Espressif esptool and a guided flash launcher.

The **SD Tune Selector** supports up to **64 `.BIN` files** from the root of a FAT32 microSD card. Only files that match the detected OneROM size can be selected.

> **Microsoft Edge download notice.** SmartScreen may warn that a file isn’t commonly downloaded when it has limited download history. If Edge or your antivirus shows a malware warning, please send the exact message and the file name or release version so I can investigate. If the GitHub page is unavailable in Edge, you can also view it in Firefox or Chrome. See [Microsoft’s SmartScreen guidance](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

1. Download the Windows kit from [the latest release](https://github.com/RapidFire-001/rapid-fire-commander/releases/latest).
2. Follow the [Windows flashing guide](WINDOWS.md) for the board check, backup, bootloader sequence and first boot.
3. Use the [menu and feature guide](HELP.md) for OneROM, SD cards, TunerPro, wideband and display settings.

This repository distributes compiled Commander firmware and documentation. See the [Commander firmware licence](FIRMWARE-LICENCE.md) for copyright and permitted use. The Commander project source and tune files are private. The kit includes separate notices and source for the third-party flasher.

Use TunerPro RT through Commander’s bridge for live calibration edits with compatible OneROM hardware. Use the bench procedure for SD tune swaps, full BIN uploads, and new board combinations. Keep OneROM disconnected from the ECU and verify the readback before reconnecting it. See the [TunerPro bridge and Bench Tune Selector instructions](HELP.md#tunerpro-bridge).
