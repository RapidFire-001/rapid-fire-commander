# Rapid Fire wired P4 wideband sources

The merged P4 image includes the wired TunerPro bridge, SD Tune Selector and a receive-only serial wideband input for the dash. See the package's main guide for P4 flashing and mode selection.

1. Confirm that the wideband unit is an LM-2 and use its MTS Serial OUT. Use the Innovate 38400 cable with an RS-232 receiver that provides a 3.3 V UART output.
2. With power off, connect that receiver's logic output to P4 JP1 pin 19 (GPIO32) and its logic ground to JP1 pin 5. Use the receiver's specified supply. RS-232 levels must stay on the receiver's RS-232 side.
3. Power the LM-2 normally. Open **Wideband** and select **Source: LM-2**. The receiver uses 19,200 baud, 8N1 and displays the first channel's lambda and AFR when a valid sample is present.
4. Compare the P4 readings with the LM-2 screen on the bench. The dash shows dashes during sensor warm-up, errors and lost input.

For an AEM X-Series 30-0300, use its blue RS-232 serial output and the same type of level receiver and P4 pins. Connect one wideband at a time. Set the gauge to AFR display and select **Source: AEM**. The P4 listens at 9,600 baud and derives lambda using the AEM manual's gasoline AFR reference of 14.65. The dash returns to LM-2 after reboot.

This package feeds the P4 display. Sending wideband and GT data to TunerPro requires a separate telemetry connection and ADX adaptation. Both wideband sources need physical verification.
