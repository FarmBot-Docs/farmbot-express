---
title: "Left Gantry Column"
slug: "left-gantry-column"
description: "Pre-assembly instructions for the FarmBot Express and Express XL left gantry column"
---


![left gantry column assembled](_images/left_gantry_column_assembled.jpg)

# Component list

|Component                         |Qty |
|----------------------------------|----|
|[[Gantry Wheel Plate]]            |1
|[[Gantry Column]]                 |1
|[[Gantry Plate Spacer Block]]     |1
|[[Idler Pulleys]]                 |4
|[[Left Gantry Corner Bracket]]    |1
|[[50mm Horizontal Motor Housing]] |1
|[[NEMA 17 Motor]]                 |1
|[[20 Tooth GT2 Pulley]]           |1
|[[Electronics Box Subassembly]]   |1
|[[X1 Motor Cable]]                |1
|[[Seed Trough Holder]]            |1
|[[50mm Cable Carrier Mount]]      |1
|[[Barbed Adapter]]                |2
|[[Pressure Regulator]]            |1
|[[Solenoid Valve]]                |1
|[[Solenoid Valve Mount]]          |1
|[[Solenoid Valve Cable]]          |1
|[[200mm Zip Ties]]                |2
|[[M5 x 40mm Screw]]               |4
|[[M5 x 20mm Screw]]               |4
|[[M5 x 16mm Screw]]               |4
|[[M5 x 10mm Screw]]               |16
|[[M5 Flange Locknut]]             |6
|[[M5 x 14.5mm Spacer]]            |2
|[[M3 x 12mm Screw]]               |4
|[[60mm Nut Bar]]                  |5
|[[40mm Nut Bar]]                  |1
|[[10mm Nut Bar]]                  |6

# Step 1: Mount the idler pulleys

Mount two [[idler pulleys]] to the [[gantry wheel plate]] using two [[M5 x 40mm screws]], two [[M5 flange locknuts]], and the [[gantry plate spacer block]] as a spacer.

![left gantry column spacer block](_images/left_gantry_column_spacer_block.jpg)

Mount the other two idler pulleys with M5 x 40mm screws and M5 flange locknuts, this time using two [[M5 x 14.5mm spacers]].

![left gantry column idlers](_images/left_gantry_column_idlers.jpg)

# Step 2: Attach the gantry column

Lightly screw four [[M5 x 20mm screws]] to two [[60mm nut bars]]. The nut bars should be loose enough to slide into the end of an extrusion in the next step.

![left gantry column nut bars](_images/left_gantry_column_nut_bars.jpg)

Slide the [[gantry column]] onto the assembly, ensuring the cut end of the extrusion fits flush against the horizontal stop on the [[gantry plate spacer block]]. Then tighten the four M5 x 20mm screws.

![left gantry column attachment](_images/left_gantry_column_attachment.jpg)

# Step 3: Attach the gantry corner bracket

Attach the left [[gantry corner bracket]] to the [[gantry column]] using three [[60mm nut bars]] and six [[M5 x 10mm screws]]. The top of the extrusion should be aligned with the notch in the corner bracket.

{% include gallery.html images="
![left gantry column Corner Bracket](_images/left_gantry_column_corner_bracket.jpg)
![right gantry column notch](_images/right_gantry_column_notch.jpg)
" %}

_The top of the extrusion should be aligned with the notch in the corner bracket._

# Step 4: Attach the X1 motor

Insert the shaft of the [[motor]] into the hole in the center of the [[gantry corner bracket]]. The motor connector should be facing down, towards the gantry wheel plate.

![Motor](_images/motor.jpg)

Slide the [[horizontal motor housing]] over the top of the motor. The open end of the motor housing should be facing down, towards the gantry wheel plate.

![left gantry column Motor Housing](_images/left_gantry_column_motor_housing.jpg)

Secure the motor and housing in place with four [[M3 x 12mm screws]].

![left gantry column Motor screws](_images/left_gantry_column_motor_screws.jpg)

Slide the [[pulley]] onto the motor shaft, ensuring the two setscrews are aligned with the flat sides of the motor shaft. The pulley's toothed area should be aligned with the large holes in the extrusion such that the belt can be routed through the extrusion without rubbing. Then tighten the setscrews.

{% include gallery.html images="
![Pulley](_images/pulley.jpg)
![left gantry column Pulley top](_images/left_gantry_column_pulley_top.jpg)
" %}

_The pulley's toothed area should be aligned with the large holes in the extrusion such that the belt can be routed through the extrusion without rubbing._

# Step 5: Attach the electronics box

Attach the [[electronics box]] to the [[gantry column]] using four [[M5 x 10mm screws]] and [[10mm nut bars]].

![electronics box](_images/electronics_box.jpg)

# Step 6: Wire up the X1 motor

Attach the X1 [[motor cable]] to the **X1 motor**. Then route the cable behind the left side of the electronics box, under it, and up into the box through the middle hole in the **supergland**.

![X1 motor cable](_images/x1_motor_cable.jpg)

Attach the cable to the `X1` motor connector on the bottom left edge of the [[Farmduino Express]] board.

![x1 motor cable plugged in](_images/x1_motor_cable_plugged_in.jpg)

# Step 7: Attach the solenoid valve

Screw the [[pressure regulator]] onto the outlet of the [[solenoid valve]].

![solenoid valve with pressure regulator](_images/solenoid_valve_with_pressure_regulator.jpg)

Screw **barbed adapters** onto the inlet of the solenoid valve and the outlet of the pressure regulator.

![solenoid valve with pressure regulator and barbed adapters](_images/solenoid_valve_with_pressure_regulator_and_barbed_adapters.jpg)

Attach the [[solenoid valve]] to the [[solenoid valve mount]] using two [[200mm zip ties]].

![solenoid valve mounted with zip ties](_images/solenoid_valve_mounted_with_zip_ties.jpg)

Attach the [[solenoid valve mount]] to the [[gantry column]] using two [[M5 x 10mm screws]] and [[10mm nut bars]]. The X1 motor cable should be routed between the mount and the box. The mount should be vertically aligned on the column such that the top barbed adapter is aligned with the top of the electronics box.

{% include gallery.html images="
![Valve mounted to column](_images/valve_mounted_to_column.jpg)
![valve mounted to column side view](_images/valve_mounted_to_column_side_view.jpg)
" %}

_The mount should be vertically aligned on the column such that the top barbed adapter is aligned with the top of the electronics box._

Connect the [[solenoid valve cable]] to the [[solenoid valve]]. Then route the cable under the electronics box and up into the box through the third from left hole in the **supergland**.

![Solenoid valve cable](_images/solenoid_valve_cable.jpg)

Connect the other end of the cable into the `WATER` peripheral connector on the [[Farmduino Express]].

![Solenoid valve cable plugged in](_images/solenoid_valve_cable_plugged_in.jpg)

# Step 8: Attach the seed trough holder

Attach the [[seed trough holder]] to the [[gantry column]] using two [[M5 x 16mm screws]] and one [[40mm nut bar]]. The top of the seed trough holder should be aligned with the top of the [[gantry plate spacer block]].

![seed trough](_images/seed_trough.jpg)

# Step 9: Attach the 50mm cable carrier mount

Attach the [[50mm cable carrier mount]] to the [[gantry wheel plate]] using two [[M5 x 16mm screws]] and [[M5 flange locknuts]].

![CC mount](_images/cc_mount.jpg)
