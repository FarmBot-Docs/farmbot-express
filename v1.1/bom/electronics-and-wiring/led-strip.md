---
title: "LED Strip"
slug: "led-strip"
description: "This LED strip is strung through the gantry's horizontal cable carrier supports so that you can light up your garden at night to show friends or for easy harvesting. Please note: this is not a grow light."
variants: 1.2m|2.4m
price: $20.00|$40.00
quantity:
  standard: 1|0
  xl: 0|1
specs:
  light color: White 6000K
  strip length: 1.2m|2.4m
  lead length: 0.7m
  cable: 22/2 Stranded Copper, Red and Black cores
  cable color: Black
  connector: Black 2-pin plug (<a href='https://www.molex.com/molex/products/part-detail/crimp_housings/0050579402'>Molex 50579402</a>)
  heatshrink label: LED
internal-specs:
  internal part name: LED Strip - 24V, 1.2m (Express)|LED Strip - 24V, 3.0m (Express XL)
  rev: A|A
  cost: $6.60|$12.00
  notes: New connector on Farmduino end, see drawing. LED strip should NOT have an adhesive backing. Cut end must be dipped in silicon to seal.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connector    |Connect the LED strip to a Farmduino peripheral plug.|Part should connect as expected|N/A
|Cable color  |Inspect the color of the cable.|Black|N/A
|Cable length |Measure the length of the cable using a measuring tape.|0.7m|+/- 20mm
|Heatshrink label|Inspect the label near the connector.|LED|N/A
|LED color    |Turn on an LED strip and inspect the color of the light.|Cool white (6000K)|N/A
|LED strip length|Measure the length of the LED strip using a measuring tape.|See BOM spec|+/- 30mm
|LED strip cut end|Inspect the cut end of the LED strip.|Cut end should be sealed with silicon rubber|N/A
|Double-sided tape|Inspect the LED strip for double-sided tape.|The part should not have any tape or other adhesives along its length|N/A
