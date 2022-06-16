# TWRP Recovery Device Tree & Kernel
* C-Force C-SMART CF011S Smart Screen

## NOTE: Still a WIP!(Work In Progress)

## Device Specifications

| Specifications          | C-Force C-Smart CF011S Smart Screen                                 |
| ----------------------- | :-----------------------------------------------------------------: |
| Codename                | SMART-SCREEN                                                        |
| Chipset / SoC           | Sunxi(sun50iw6p1) Allwinner H6 (28 nm)                              |
| CPU                     | 4 x Cortex-A53 (Revision r0p4)                                      |
| GPU                     | Mali-T720 MP2 @ 600Mhz                                              |
| Memory                  | 2 GB DDR4                                                           |
| Shipped Android version | 9.0 (Android Pie)                                                   |
| Internal Storage        | 16GB eMMc                                                           |
| MicroSD                 | Up to 64 GB                                                         |
| USB                     | 1x USB-A, 2x USB-C (1x USB-C Reserved for Power)                    |
| Battery                 | Wall Plug                                                           |
| Dimensions              | 14.57 x 8.66 x 0.24 inches                                          |
| Display                 | 15.6 inch 1080p IPS, 1920 x 1080 pixels, 16:9 Aspect Ratio          |
| Treble Supported        | Yes                                                                 |
| VNDK Version            | 28.0                                                                |

## Treble Info:

![Treble Info Readout](Screenshot_TrebleInfo.png)

## CPU-Z Readout:

* SoC
![CPU-Z SoC](Screenshot_cpuz-soc.png)

* Device
![CPU-Z Device](Screenshot_cpuz-device.png)

* System
![CPU-Z System](Screenshot_cpuz-system.png)

### Additional Technical Specs (Wiki):
```
Allwinner H6 SoC Features
    CPU
        ARM Cortex-A53 Quad-Core
        512KB L2-Cache (shared between four cores)
        32 KB (Instruction) / 32KiB (Data) L1-Cache per core
        SIMD NEON, VFP4
        Virtualization
    GPU
        ARM Mali-T720 MP2
        Featuring 2 unified shader cores
        Complies with OpenGL ES 3.1, OpenCL 1.1
    Memory
        DDR3/DDR4/LPDDR2/LPDDR3 controller
        NAND Flash controller and 64-bit ECC, supports full disk encryption
        3 MMC controllers, in which MMC2 (eMMC controller) supports full disk encryption
    Video
        Ultra HD 4k and Full HD 1080p video decoding of MPEG-2, MPEG-4 SP/ASP GMC, H.263, H.264, H.265, WMV9/VC-1, and VP8
        BD Directory, BD ISO and BD m2ts video decoding
        H.264 High Profile 1080P@60fps encoding
        3840×1080,1920x2160 3D decoding
        Complies with RTSP, HTTP,HLS,RTMP,MMS streaming media protocol
    Display
        Integrated HDMI V2.0 with HDCP2.2 4K@60fps
        TV CVBS output
        RGB LCD output
    Camera
        Integrated parallel 8-bit I/F YUV422 sensor
        Support CCIR656 protocol fot NTSC and PAL
        5M CMOS sensor support
        Support video capture resolution up to 1080p@30fps
    Audio
        Two audio digital-to-analog(DAC) channels 92dB SNR
        Two differential microphone inputs (one low-noise)
        Stereo Linein input
        TDM Digital Microphone input
    Embedded Controller:
        AR100 controller.
    * Thermal Sensor Controller (TSC) providing over-temperature protection interrupt and over-temperature alarm interrupt
    - AXP805 PMIC
    - package: FBGA451, 15 mm x 15 mm, 0.65 mm Pitch
```

### Links:

[Linux Sunxi Wiki](https://linux-sunxi.org/H6)

[CForce Link](https://cforcedesign.com/collections/frontpage/products/c-smart-the-world-s-first-portable-android-touch-display)

[Amazon Link](https://www.amazon.com/CF011S-Portable-Assistant-15-6inch-Compatible/dp/B08HQRNCDV)

## Copyright

```
 /*
 *  Copyright (C) 2013-22 The TWRP
 *
 * This program is free software: you can redistribute it and/or modify
 * it under the terms of the GNU General Public License as published by
 * the Free Software Foundation, either version 3 of the License, or
 * (at your option) any later version.
 *
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU General Public License for more details.
 *
 * You should have received a copy of the GNU General Public License
 * along with this program.  If not, see <http://www.gnu.org/licenses/>.
 *
 */
 ```
