---
title: MMC5983MA Compass Module
product_description: "A compact external three-axis magnetometer for drones, robotics, and embedded navigation systems, built around the MEMSIC MMC5983MA."
description: "Compact three-axis compass with low-ripple regulation, ESD-protected I²C, and selectable pull-ups."
permalink: /products/mmc5983ma/
toc: true
toc_sticky: true
sidebar:
  nav: products
gallery:
  - url: /assets/images/compass-1.jpg
    image_path: /assets/images/compass-1.jpg
    alt: "MMC5983MA compass module and protective enclosure"
  - url: /assets/images/compass-2.jpg
    image_path: /assets/images/compass-2.jpg
    alt: "Additional view of the MMC5983MA compass module"
---

{{ page.product_description | markdownify }}

[Buy on Tindie](https://www.tindie.com/products/tm8lab/low-noise-magnetometercompass-mmc5983ma/){: .btn .btn--primary}

{% include product-gallery.html %}

## Features

- MMC5983MA three-axis magnetometer.
- TLV77333 low-ripple onboard regulator for cleaner sensor power.
- USBLC6 ESD protection on the I²C lines.
- Solder-jumper-selectable SDA/SCL pull-up resistors.
- Compact PCB with a lightweight, 3D-printed protective enclosure.

## Interface and specifications

| Item | Detail |
| --- | --- |
| Sensor | MEMSIC MMC5983MA |
| Interface | I²C |
| I²C address | `0x30` |
| Communication test | All units tested at 400 kHz, as stated in our listing |
| Regulator | TLV77333 |
| I²C protection | USBLC6 |
| Pull-ups | Selectable using solder jumpers |

Supply-voltage limits, connector pinout, board dimensions, and sensor-axis orientation still need a verified integration guide. Confirm these details with TM8 Lab before connecting the module.
{: .notice--info}

## Compatibility

The module can be used with flight controllers and embedded systems supporting the MMC5983MA/MMC5XX3 family, including compatible ArduPilot systems. Compatibility depends on the specific controller, firmware, and electrical interface; a tested hardware/firmware matrix is not yet published.

## Protective enclosure

The enclosure provides electrical insulation and mechanical protection. The board arrives press-fitted into one half; you can choose to use the enclosure or operate the sensor without it.

To close the enclosure, press the other half into place with gentle, even pressure. It is intended as a one-time closure: reopening it can break its retaining pins.

## Documentation

Verified wiring, axis-orientation, calibration, and firmware-specific setup instructions will be added here. Until those are available, use the Tindie listing's contact option for integration questions.

[View listing and contact TM8 Lab](https://www.tindie.com/products/tm8lab/low-noise-magnetometercompass-mmc5983ma/)
