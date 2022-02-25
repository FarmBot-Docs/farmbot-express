---
title: "Motor Cable"
slug: "motor-cable"
description: "These 4-wire cables connect each NEMA 17 stepper motor to the Farmduino. They are labelled on the Farmduino end X1, X2, Y, and ZY. The Z-axis cable is split into a Y-axis section labelled ZY and a Z-axis section labelled ZZ that connect with a 90-degree screw-together waterproof connection at the cross-slide."
variants: X1, 0.7m|X2, 1.8m|Y, 2.2m|ZY, 2.1m|X2, 3.0m|Y, 3.4m|ZY, 3.3m|ZZ, 1.8m
price: $20.00|$23.00|$25.00|$27.00|$28.00|$30.00|$32.00|$24.00
quantity:
  express: 1|1|1|1|0|0|0|1
  xl: 1|0|0|0|1|1|1|1
specs:
  length: 0.7m|1.8m|2.2m|2.1m|3.0m|3.4m|3.3m|1.8m
  Cores: 4
  Gauge: 18
  Motor connector: 6 pin connector (only 4 pins used)
  Intermediate connector: 4-pin waterproof screw together 90 degree connectors. (female connector on the Y-Axis sections, male connector on the Z-Axis section)
  Farmduino connector: 2.54mm pitch 4-pin connector with locking tab (<a href="https://www.molex.com/molex/products/part-detail/crimp_housings/0050579404">Molex Part 50579404</a>)
  Outer color: Black
  Inner Colors: Black, Red, Yellow, White
  Label: X1|X2|Y|ZY|X2|Y|ZY|ZZ
internal-specs:
  internal part name: "Motor Cable - X1, 0.7m (Express and Express XL)|
  Motor Cable - X2, 1.8m (Express)|
  Motor Cable - Y, 2.2m (Express)|
  Motor Cable - ZY, 2.1m (Express)|
  Motor Cable - X2, 3.0m (Express XL)|
  Motor Cable - Y, 3.4m (Express XL)|
  Motor Cable - ZY, 3.3m (Express XL)|
  Motor Cable - ZZ, 1.8m (Express and Express XL)|"
  cost: $1.60|$2.10|$1.80|$3.90|$2.90|$3.10|$4.70|$3.80
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the cable's diameter using digital calipers.|5mm|+/- 1mm
|Connectors   |Use a motor cable to connect a motor to the Farmduino. Issue some movement commands.|The motor should operate as expected|N/A
|Label        |Inspect the shrinkwrap labels.|X1, X2, Y, ZY, and ZZ|N/A
|Cable        |Inspect the cable's spec.|24AWG-4C stranded copper cable|N/A
|Color        |Inspect the color of the cable.|Black|N/A
