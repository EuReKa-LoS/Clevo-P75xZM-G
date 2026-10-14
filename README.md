# Clevo-P75xZM-G

**Unlocked and Modified BIOS for the Clevo P750ZM-G**

## Overview

Hello!
First of all, this is my first attempt at modifying a BIOS on my own.

I've owned a Clevo P750ZM-G since late 2015 and experienced several thermal issues due to excessive voltage and limitations in the stock BIOS.
I delidded the CPU and applied liquid metal to my golden-sample Intel Core i7-4790K, but temperatures still reached 82°C under stress testing.
With this modified BIOS, I was able to undervolt the CPU and reduce temperatures to 71°C under the same stress-testing conditions.

My laptop has also been upgraded with an NVIDIA GeForce GTX 1070.

## Features and Modifications

- Unlocked BIOS settings, including CPU undervolting.
- Added NVMe support via an additional DXE module.
- Updated Intel RST components (September 2026).
- Updated CPU microcode (September 2026) for the following processors:
  - Intel Core i5-4690
  - Intel Core i5-4690K
  - Intel Core i7-4790
  - Intel Core i7-4790S
  - Intel Core i7-4790K
- Modified BIOS splash screen.

## Flashing Information

- **Tested flash chip size:** 8 MB
- **Flashing tool:** CH341A programmer

The BIOS has been tested on an 8 MB flash chip using an external CH341A programmer.

Compatibility with other flash chip sizes and hardware configurations has not yet been confirmed.

## Work in Progress

- Adapt the BIOS for 16 MB flash chips.
- Investigate GPU compatibility and potential compatibility limitations.

## Disclaimer

This is a community modification provided as-is.
Flashing a modified BIOS carries a risk of rendering your system unbootable.

Make sure to back up your original BIOS before flashing and ensure that you have a recovery method available.
Use this BIOS at your own risk.
