---
title: Battery-Powered Breadboard Power Supply
description: "Portable CR123A breadboard supply with 5.1 V and 3.3 V rails, adjustable DAC output, and OLED current monitoring."
permalink: /products/breadboard-power/
toc: true
toc_sticky: true
sidebar:
  nav: products
gallery:
  - url: /assets/images/breadboard-1.jpg
    image_path: /assets/images/breadboard-1.jpg
    alt: "Breadboard power supply with OLED display"
  - url: /assets/images/breadboard-2.jpg
    image_path: /assets/images/breadboard-2.jpg
    alt: "Illustration of breadboard power outputs and maximum tested current ratings"
---

Less cables, more fun. Power low-power breadboard projects from a single CR123A battery, with two fixed voltage rails, an adjustable analog output, and current monitoring on an onboard OLED display.

[Buy on Tindie](https://www.tindie.com/products/tm8lab/battery-powered-breadboard-power-supply/){: .btn .btn--primary}

**Battery requirement:** Use one CR123A 3 V primary lithium battery. Do not use rechargeable 3.7 V 16340/RCR123A Li-ion cells. Battery and breadboard are not included.
{: .notice--warning}

{% include gallery %}

## Features

- Dedicated TPS61023 boost converter for the nominal 5.1 V rail.
- Separate boost converter and TLV77333 high-PSRR linear regulator for the 3.3 V rail.
- Adjustable analog output using the MSPM0G1506 microcontroller's integrated 12-bit DAC.
- High-side current measurement: output current is displayed in milliamps while ground remains undisturbed.
- 0.5-inch OLED display and user-accessible analog-output recalibration.
- MOSFET-based high-side power switching with reverse-battery protection.

## Specifications

These values follow the TM8 Lab Tindie listing. Maximum output currents depend on the battery and operating conditions.

| Item | Detail |
| --- | --- |
| Battery | 1 × CR123A, 3 V primary lithium |
| Fixed rail 1 | Nominal 5.1 V; maximum tested output 500 mA |
| Fixed rail 2 | Nominal 3.3 V; maximum tested output 250 mA |
| Analog setpoint | 1–1400 mV in 1 mV increments |
| DAC resolution | 12-bit |
| Current-sense resistors | 0.2 Ω |
| Display | 0.5-inch OLED |
| Dimensions | 51 × 51 × 22 mm |
| Weight | Approximately 14 g including battery holder clip, excluding battery |

Available current depends on battery internal resistance, battery condition, temperature, and load. It decreases as the battery becomes depleted. The maximum values are not guaranteed simultaneous continuous ratings for every battery.

## Adjustable analog output

The DAC output is useful for analog biasing, ADC input testing, programmable setpoints, and low-voltage analog experiments.

**1 mV is the setpoint increment, not guaranteed absolute accuracy.** The DAC has limited output-current capability and is not a general-purpose power rail. Actual output accuracy and minimum achievable voltage depend on DAC limitations and load conditions.
{: .notice--info}

## Breadboard compatibility

The module supplies 5.1 V to the top power rails, 3.3 V to the bottom power rails, and the DAC output to the main terminal-strip holes, in the orientation shown in the listing.

**It does not fit every breadboard layout.** Compare your breadboard with this compatibility drawing before ordering or connecting it.

![Compatible breadboard hole layout from the TM8 Lab listing]({{ '/assets/images/breadboard-compatibility.jpg' | relative_url }})

## Battery and safe operation

- Observe the indicated battery polarity.
- Use only the specified CR123A primary battery.
- Avoid short-circuiting outputs or connecting external power sources directly to them.
- Battery runtime varies with load, battery brand, condition, and temperature.
- Intended for low-voltage electronics experimentation and prototyping, not safety-critical applications.

## Package contents

- One breadboard power supply unit.
- One CR123A battery holder clip.

First-batch units may have minor cosmetic imperfections or visible no-clean flux residue.

## Documentation

A detailed button-operation and recalibration guide is still being prepared. For operating questions, contact TM8 Lab through the listing before use.

[View listing and contact TM8 Lab](https://www.tindie.com/products/tm8lab/battery-powered-breadboard-power-supply/)
