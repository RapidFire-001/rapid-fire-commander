# Rapid Fire Commander

[Download the printable Commander booklet (PDF)](Rapid-Fire-Commander-Booklet.pdf). The numbered A5 pages are designed to fold from A4 in your PDF reader’s Booklet print mode.

Rapid Fire Commander is a wired ESP32-P4 dashboard and OneROM tuning utility with read-only Holden ALDL logging through TunerPro RT.

Wired dashboard and OneROM tuning utility for the Guition JC4880P443C_I_W/Y 4.3-inch ESP32-P4 display. The Windows kit includes Commander v0.13, Espressif esptool and a guided flash launcher.

**TunerPro + GT Pro** mode provides separate COM ports for OneROM emulation and read-only Holden ALDL logging. Load the matching ADX in TunerPro RT. See the [ADX logging setup](HELP.md#tunerpro--gt-pro-adx-logging).

The **SD Tune Selector** supports up to **64 `.BIN` files** from the root of a FAT32 microSD card. Only files that match the detected OneROM size can be selected.

> **Microsoft Edge download notice.** SmartScreen may warn that a file isn’t commonly downloaded when it has limited download history. If Edge or your antivirus shows a malware warning, please send the exact message and the file name or release version so I can investigate. If the GitHub page is unavailable in Edge, you can also view it in Firefox or Chrome. See [Microsoft’s SmartScreen guidance](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

For a Delco 808 wired directly to OneROM, select **ALDL 808 DT** in the Rapid Fire OneROM app. If you use GT Pro for logging, select its separate acquisition COM port and the matching ADX in TunerPro RT. See the [Commander help guide](HELP.md) for setup.

| OneROM firmware mode | Use |
| --- | --- |
| **NORMAL DT** | Honda standard Ostrich with Display Trace. The optional UART runs at 38,400 baud. |
| **ALDL 808 DT** | Delco 808 wired directly to OneROM for ALDL at 8,192 baud, with default signal polarity. |

1. Download the Windows kit from [the latest release](https://github.com/RapidFire-001/rapid-fire-commander/releases/latest).
2. Follow the [Windows flashing guide](WINDOWS.md) for the board check, backup, bootloader sequence and first boot.
3. Use the [menu and feature guide](HELP.md) for OneROM, SD cards, TunerPro, wideband and display settings.

This repository distributes compiled Commander firmware and documentation. See the [Commander firmware licence](FIRMWARE-LICENCE.md) for copyright and permitted use. The Commander project source and tune files are private. The kit includes separate notices and source for the third-party flasher.

Use TunerPro RT through Commander’s bridge for live calibration edits with compatible OneROM hardware. OneROM can stay installed in the vehicle’s MemCal for SD tune swaps and full BIN uploads. Keep the engine off and verify the readback before starting it. See the [TunerPro bridge and SD Tune Selector instructions](HELP.md#tunerpro-bridge).

## Support

For help with this software, email [Rapid Fire Software Support](mailto:support@rapidfiresoftware.net). Include the software version, what you were trying to do, and any error message you saw.
