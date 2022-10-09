---
title: "Plug Everything In"
slug: "plug-everything-in"
---


{%
include callout.html
type="warning"
title="Power should still be disconnected"
content="At this time, FarmBot should not be plugged into any power source."
%}

# Step 1: Connect the Y motor

Route the Y [[motor cable]] through the slot in the [[cross-slide plate]] and connect it to the **Y motor**.

![plug in the y motor cable to the y motor](_images/plug_in_y_motor.png)

# Step 2: Connect the water tubes

Connect the [[water tube]] coming from the y-axis [[cable carrier]] to the [[90-degree barb]] and the [[NPT to barb adapter]] above the [[solenoid valve]].

{% include gallery.html images="
![water tubes y axis connection](_images/water_tubes_y_axis_connection.png)
![water tubes solenoid valve connection](_images/water_tubes_solenoid_valve_connection.png)
" %}

Connect the [[water tube]] coming from the top of the x-axis [[cable carrier]] to the [[NPT to barb adapter]] below the [[solenoid valve]].

![water tubes solenoid valve bottom barb connection](_images/water_tubes_solenoid_valve_bottom_barb_connection.png)

Screw the [[garden hose to barb adapter]] onto a **garden hose** of the appropriate length. Then connect the [[water tube]] coming from the bottom of the x-axis [[cable carrier]] to the [[garden hose to barb adapter]].

![water tubes garden hose connection](_images/water_tubes_garden_hose_connection.png)

# Step 3: Check for leaks

Turn on the supply of water at your **garden hose spigot** and check the FarmBot for any leaks. If your municipal water pressure is abnormally high, you may need to add [[zip ties]] to the tube-to-barb connections to prevent the tubes from popping off. In rare circumstances you also may need to add plumber's tape (PTFE tape) to the threaded connections at the hose or solenoid valve to prevent leaking.

# Step 4: Connect the Z-axis cables

Connect the cables at the junction of the y-axis and z-axis cable carriers:

* **Vacuum pump cables** labeled `VAC`
* **Z motor cables** labeled `ZY` and `ZZ`
* **Camera cables** labeled `CAM`

{%
include callout.html
type="danger"
title="The camera and z motor cables use the same connectors"
content="Pay close attention to the cable labels to ensure you are connecting `CAM` to `CAM` and `ZY` to `ZZ`. **Take your time with this step because a mistake could permanently damage the electronics.**"
%}

{% include gallery.html images="
![yz vacuum pump connection](_images/yz_connection_vacuum_pump.png)
![yz z motor connection](_images/yz_connection_z_motor.png)
![yz camera connection](_images/yz_connection_camera.png)
" %}

Pay special attention that you fully insert the 90-degree connectors together. This may require a multi-step process of pushing together, slightly tightening the thumb screws, pushing together again, and tightening some more. See the video below for detail.

{% include youtube.html id="rPqgmoE3PbI" %}

# Step 5: Route the X2 motor cable and LED strip

Attach the **X2** [[motor cable]] to the **X2** [[motor]]. Then route the cable and the [[LED strip]] through the [[30mm horizontal cable carrier supports]] along the [[gantry main beam]].

![x2 motor cable and led strip routing](_images/x2_motor_cable_and_led_strip_routing.png)

# Step 6: Route all cables behind the electronics box

Route all of the cables down between the [[solenoid valve mount]] and the [[electronics box]]. You may need to temporarily disconnect the solenoid valve mount from the extrusion to facilitate fitting all of the cables in the space.

![cables routed behind electronics box](_images/cables_routed_behind_electronics_box.png)

# Step 7: Plug everything in

{%
include callout.html
type="danger"
title="Power should still be disconnected"
content="At this time, the FarmBot should not be plugged into any power source."
%}

The diagram below illustrates the FarmBot Express electronics schematic. In the following steps you'll connect each motor and peripheral one at a time, and finally the power supply.

![express electronics schematic](_images/express_electronics_schematic.png)

Connect the peripheral cables to the [[Farmduino Express]] board. From left to right:

* [[Vacuum pump cable]] labeled `VAC` to the `VACUUM` connector.
* [[Solenoid valve cable]] labeled `H20` to the `WATER` connector.
* [[LED strip]] labeled `LED` to the `LIGHTING` connector.

![plug in the peripherals](_images/plug_in_peripherals.png)

Connect the [[motor cables]] to the [[Farmduino Express]] board. From left to right:

* Cable labeled `X1` to the `X1 MOTOR` connector. (this should be pre-connected)
* Cable labeled `X2` to the `X2 MOTOR` connector.
* Cable labeled `Y` to the `Y MOTOR` connector.
* Cable labeled `ZY` to the `Z MOTOR` connector.

![plug in the motors](_images/plug_in_motors.png)

Connect the [[camera cable]] to one of the **vertically oriented** USB Type-C connectors labeled `USB1` or `USB2` on the [[Farmduino Express]] board.

{%
include callout.html
type="warning"
title="Do not use the horizontally oriented USB Type-C connector"
content="Plugging the camera into the **horizontally oriented** connector will prevent the Raspberry Pi from communicating with the Farmduino."
%}

![plug in the camera](_images/plug_in_camera.png)

Connect the [[power supply cable]] to the `24V POWER IN` connector on the [[Farmduino Express]] board.

![plug in the power cable](_images/plug_in_power.png)

# Step 8: Flash FarmBot OS to the microSD card

Remove the [[micro SD card]] from the **Raspberry Pi Zero** and follow our [FarmBot OS installation instructions](https://software.farm.bot/docs/farmbot-os#installing-farmbot-os) to install the latest version of our software. Then reinsert the microSD card into the Pi.

![microSD card in pi zero slot](_images/microsd_card_in_pi_zero_slot.png)

# Step 9: Mount the power supply

Mount the [[power supply]] to the **bed** using four [[wood screws]]. Then connect the **power supply's output** to the [[power supply cable]].

![power supply mounted](_images/power_supply_mounted.png)

# Step 10: Plug FarmBot into the power source

{%
include callout.html
type="danger"
title="Before plugging in..."
content="Once you plug in the power supply, your system will be powered. Once powered, you cannot add, remove, or change any motor cables, peripheral cables, etc, or you risk damaging the electronics and being electrically shocked.

If you need to make any changes, first unplug the power supply from the wall."
%}

If everything looks good, and you understand the precautions needed around powered electronics, plug the [[power supply]] into a **GFCI protected outlet**. If an appropriate outlet is not close enough to plug in directly, use an extension cord of the appropriate length and the green [[power cord protector]].

{% include gallery.html images="
![power supply power connection](_images/power_supply_power_connection.png)
![power supply cord protector](_images/power_supply_cord_protector.png)
" %}

{%
include callout.html
type="success"
title="The mark of success"
content="If all has gone well, FarmBot will begin booting up and you should see blinking lights!"
%}

{%
include callout.html
type="warning"
content="If anything seems not right, suspicious, or hazardous, **immediately unplug the power supply from the wall** and contact us at [support@farm.bot](mailto:support@farm.bot)."
%}

# What's next?

 * [Configure FarmBot](http://configure.farm.bot)
