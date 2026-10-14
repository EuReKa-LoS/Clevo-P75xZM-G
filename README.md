# Clevo-P75xZM-G

**Unlocked and Modified BIOS for the Clevo P750ZM-G**

## Overview

Hello!
First of all, this is my first attempt at modifying a BIOS on my own.

I've owned a Clevo P750ZM-G since late 2015 and experienced several thermal issues due to excessive voltage and limitations in the stock BIOS.
I delidded the CPU and applied liquid metal to my golden-sample Intel Core i7-4790K, but temperatures still reached 82°C under stress testing.
With this modified BIOS, I was able to undervolt the CPU and reduce temperatures to 71°C under the same stress-testing conditions.

My laptop has also been upgraded with an NVIDIA GeForce GTX 1070.

# Clevo-P75xZM-G

Unlocked and Modified BIOS for the Clevo P750ZM-G

## Overview

Hello!

First of all, this is my first attempt at modifying a BIOS on my own.

I've owned a Clevo P750ZM-G since late 2015 and experienced thermal issues due to excessive voltage and limitations in the stock BIOS.

I delidded the CPU and applied liquid metal to my golden-sample Intel Core i7-4790K, but temperatures still reached 82°C under stress testing.

With this modified BIOS, I was able to undervolt the CPU and reduce temperatures to 71°C under the same stress-testing conditions.

My laptop has also been upgraded with an NVIDIA GeForce GTX 1070.

## Original BIOS Dump

- **System:** Clevo P750ZM-G
- **Original BIOS Release:** 1.03.04
- **Original BIOS Date:** June 12, 2015
- **Original BIOS Version:** 00.15
- **Firmware:** AMI Aptio IV
- **Dump Method:** External SPI programmer (CH341A)

## Firmware Components

- **Intel RST EFI RAID:** 14.8.2.2397
- **Intel RST SATA Option ROM:** 14.8.2.2397
- **Intel Haswell/Broadwell VBIOS Option ROM:** 1030
- **NVMe Support:** Additional DXE module

## CPU Microcodes

Microcodes included in the modified BIOS image, as reported by the firmware analysis tool.

| CPUID | Revision | Date | Status |
|---|---|---|---|
| 306C3 | 0x28 | 2019-11-12 | PRD |
| 306C2 | FFFF0006 | 2012-10-17 | PRE |
| 306C1 | FFFF0014 | 2012-07-25 | PRE |

The `306C3` microcode corresponds to the Intel Core i7-4790K used for testing.

## Hardware Configuration Tested

- **CPU:** Intel Core i7-4790K
- **GPU:** NVIDIA GeForce GTX 1070
- **Flash Chip Size:** 8 MB


## Work in Progress

- Adapt the BIOS for 16 MB flash chips.
- Investigate GPU compatibility and potential compatibility limitations.

## Disclaimer

This is a community modification provided as-is.
Flashing a modified BIOS carries a risk of rendering your system unbootable.

Make sure to back up your original BIOS before flashing and ensure that you have a recovery method available.
Use this BIOS at your own risk.
