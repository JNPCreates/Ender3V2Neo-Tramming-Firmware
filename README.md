# JNPCREATES Ender-3 V2 Neo Tramming Firmware

Bed leveling made easy for the **Creality Ender-3 V2 Neo** (V4.2.2 board, CR Touch). Built on Marlin 2.1.2.9.

<p>
  <img src="images/tramming-results.png" width="200" alt="Bed Tramming: turn Back Right CCW 67 degrees">
  <img src="images/tramming-complete.png" width="200" alt="Tramming complete">
  <img src="images/auto-mesh-live.png" width="200" alt="Auto Mesh filling in live">
</p>

## What's added

- **Bed Tramming:** probes the four corners and tells you **one knob at a time**: which one, which way and how many degrees. Repeat until all four are green.
- **Auto Mesh 5×5:** watch the mesh fill in live. It's saved automatically. **View Mesh** shows it any time.
- **Heat bed first:** optional, so you level the bed at printing temperature.
- **Paper Leveling:** moves the nozzle over each knob for the paper test.
- **Probe Accuracy Test:** checks your CR Touch.
- **Newest file on top**, a **"Print this file?"** confirmation, and a clean print-finished screen.

## How to install

### 1. Check your screen and update it

This firmware was made and tested on a **TJC screen**. TJC screens need a one-time display update first.
Follow MRiscoC's guide to find out which screen you have and to update it: **[How to update the display](https://github.com/mriscoc/Ender3V2S1/wiki/How-to-update-the-display)**.

### 2. Flash the firmware

1. Download **[JNPCREATES-E3V2Neo-v1.0.bin](JNPCREATES-E3V2Neo-v1.0.bin)**.
2. Copy it to a FAT32 microSD card (32 GB or less) and **rename it** to a name you haven't flashed before.
3. With the printer off, insert the card and turn it on. After 10–30 seconds the screen shows **JNPCREATES**.

### 3. Set up

1. **Control → Restore Settings**, then set your **Z offset** (Prepare → Z-Offset) and, if you changed extruders, your **E-steps** (default 93).
2. **Control → Store Settings.**
3. **Leveling → Bed Tramming**, then **Leveling → Auto Mesh**.

## Credits

Built on [Marlin](https://github.com/MarlinFirmware/Marlin). Inspired by MRiscoC's Professional Firmware.
Source changes: [`JNPCREATES-Marlin-2.1.2.9.patch`](JNPCREATES-Marlin-2.1.2.9.patch). License: GPL-3.0 ([LICENSE](LICENSE)).
