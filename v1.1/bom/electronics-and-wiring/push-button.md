---
title: "Push Button"
slug: "push-button"
description: "This waterproof push button comes pre-mounted on the top of the electronics box for E-STOPing the device. The button includes a wiring harness and comes pre-connected to the Farmduino."
variants: Red|Wiring Harness|Nut|O-Ring
price: $6.00|$1.00|$0.00|$0.00
quantity:
  express: 1|1|1|1
  xl: 1|1|1|1
specs:
  color: Red|N/A|N/A|N/A
  material: Stainless steel and plastic
  Waterproof?: Yes
  O-Ring?: Included
  Wiring?: Included
internal-specs:
  internal part name: LED Push Button - Red|Push Button Wiring Harness|LED Push Button - Nut|LED Push Button - O-Ring
  cost: $2.79|$1.00|$0.00|$0.00
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Diameter     |Measure the diameter of the threaded section using digital calipers.|21.8mm|+/- 0.2mm
|Electronics box fit|Check fit in electronics box.|Button should fit with minimal play such that o-ring is guaranteed to seal.|N/A
|Length       |Measure the overall length using digital calipers.|40mm|+/- 1mm
|O-ring       |Inspect for the presence of an O-ring under the top flange.|Present|N/A
|Waterproof   |Drill a hole in a small plastic tub. Fasten the button to the hole and fill the tub with water.|The button should continue to operate when submerged, and prevent water from leaking.|N/A
|Wiring harness|Connect wiring harness between button and Pi Adapter Board.|Button should work, harness should be of adequate length, and connectors should stay firmly attached.|N/A
|Material     |Ensure the material will not rust by holding a magnet to the part.|Stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.
|Function     |Bind a button to a sequence and press the button.|FarmBot should execute the sequence|N/A
|Illumination |Power on FarmBot.|The E-stop button should be illuminated|N/A
