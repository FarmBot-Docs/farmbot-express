---
title: "LEDs"
slug: "leds"
description: "Express electronics LED reference"
---

# Farmduino Express v1.1 board LEDs

| ID        |label | source | description                   | color  | location | statuses     |
|-----------|------|--------|-------------------------------|--------|----------|--------------|
| PWR       | V8   |        | Farmduino power               | red    | board    | solid        |
| D13       | V9   | D13    | controllable LED              | green  | board    | solid        |
| SYNC      | V4   | GPIO24 | FarmBot OS sync               | green  | board    | solid, blink |
| CONNECT   | V5   | GPIO25 | FarmBot OS account connection | blue   | board    | solid, blink |
| UNLOCK    | V7   | GPIO23 | E-STOP unlock                 | yellow | board    | blink        |
| ESTOP     |      | GPIO17 | E-STOP                        | red    | box      | solid, blink |
| VACUUM    | LED3 | D9     | VACUUM power                  | green  | board    | solid        |
| WATER     | LED2 | D8     | WATER power                   | green  | board    | solid        |
| LIGHT     | LED1 | D7     | LIGHT power                   | green  | board    | solid        |
| TX        | V10  | TX0    | firmware transmit             | yellow | board    | blink        |
| RX        | V11  | RX0    | firmware receive              | green  | board    | blink        |
| FDX_LED   | D6   |        | ethernet duplex               | green  | board    | solid, blink |
| USB_LED   | D7   |        | ethernet USB                  | green  | board    | solid, blink |
| LINK_LED  |      |        | ethernet link                 | green  | eth      | solid, blink |
| SPEED_LED |      |        | ethernet speed                | yellow | eth      | solid, blink |
| X1        | X1   | D26    | X1 motor power / activity     | green  | board    | solid, blink |
| X2        | X2   | D15    | X2 motor power / activity     | green  | board    | solid, blink |
| Y         | Y    | D32    | Y motor power / activity      | green  | board    | solid, blink |
| Z         | Z    | D35    | Z motor power / activity      | green  | board    | solid, blink |
| PI        |      |        | Raspberry pi power / activity | green  | pi       | solid, blink |
