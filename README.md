# Rival 3 Wireless Recovery

Recovery utility for the SteelSeries Rival 3 Wireless flashing purple / not detected issue.

## What happened

My Rival 3 Wireless Gen 2 suddenly stopped working in both Bluetooth and 2.4 GHz modes and started flashing purple.

The original recovery utility only detected the Gen 1 USB PID, so it returned:

`Device not found`

The Gen 2 version in this repository changes the device detection from:

- Gen 1: `0x1038:0x1830`
- Gen 2: `0x1038:0x1872`

No mouse firmware was replaced or modified by this patch. The change is only for device detection in the recovery utility.

## Instructions

1. Fully close SteelSeries GG from the Windows system tray.
2. Connect the Rival 3 Wireless dongle.
3. Put the mouse in 2.4 GHz mode.
4. Run the appropriate recovery utility.
5. Wait for the success message.
6. Open SteelSeries GG.
7. Go to Engine and install any firmware or critical update that appears.

## Downloads

Download the appropriate file from the Releases section:

- Gen 1: original recovery utility
- Gen 2: use the file marked `Gen2`

## Disclaimer

This is an unofficial community fix and is not affiliated with or endorsed by SteelSeries.

Use these files at your own risk.

The Gen 1 utility was originally obtained from a third-party source. The Gen 2 version was created by modifying only the device detection so that the utility can recognize the Rival 3 Wireless Gen 2.
