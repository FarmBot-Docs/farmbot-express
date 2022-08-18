---
title: "Plug Everything In"
slug: "plug-everything-in"
---


{%
include callout.html
type="warning"
title="Power should still be disconnected"
content="At this time, the FarmBot should not be plugged into any power source."
%}

# Step 1: Connect the Y motor

Route the **Y motor cable** through the slot in the **cross-slide plate** and connect it to the **Y motor**.

![y axis motor cable highlighted](_images/y_axis_motor_cable_highlighted.png)

# Step 2: Connect the water tubes

Connect the **water tube** coming from the **y-axis cable carrier** to the **90 degree barb** and the **barbed adapter** above the **solenoid valve**.

{% include gallery.html images="
![water tubes y axis connection](_images/water_tubes_y_axis_connection.png)
![water tubes solenoid valve connection](_images/water_tubes_solenoid_valve_connection.png)
" %}

Connect the **water tube** coming from the top of the **x-axis cable carrier** to the **barbed adapter** below the **solenoid valve**.

![water tubes solenoid valve bottom barb connection](_images/water_tubes_solenoid_valve_bottom_barb_connection.png)

Screw the **garden hose to barb adapter** onto a **garden hose** of the appropriate length. Then connect the **water tube** coming from the bottom of the **x-axis cable carrier** to the **garden hose to barb adapter**.

![water tubes garden hose connection](_images/water_tubes_garden_hose_connection.png)

# Step 3: Check for leaks

Turn on the supply of water at your **garden hose spigot** and check the FarmBot for any leaks. If your municipal water pressure is abnormally high, you may need to add **zip-ties** to the tube-to-barb connections to prevent the tubes from popping off. In rare circumstances you also may need to add plumber's tape (PTFE tape) to the threaded connections at the hose or solenoid valve to prevent leaking.

# Step 4: Connect the Z-axis cables

Connect the **Z motor cables** together, the **camera cables** together, and the **vacuum pump cables** together.

{%
include callout.html
type="danger"
title="CAUTION: The camera and z motor cables use the same connectors"
content="Note that the camera and Z motor cables use the same connectors. When connecting the ends coming from the y-axis cable carrier to the ends coming from the z-axis cable carrier, ensure you are connecting camera to camera and Z motor to Z motor.

You can check to see which cable is which by tugging on a cable on one end of the cable carrier and seeing which cable moves on the other end.

**We strongly recommend you take your time with this step because a mistake could cause massive damage to your electronics.**"
%}

![y axis cable connections](_images/y_axis_cable_connections.png)

Pay special attention that you fully insert the 90-degree connectors together. This may require a multi-step process of pushing together, slightly tightening the thumb screws, pushing together again, and tightening some more. See the video below for detail.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FrPqgmoE3PbI%3Ffeature%3Doembed&display_name=YouTube&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DrPqgmoE3PbI&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FrPqgmoE3PbI%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" title="YouTube embed" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>

# Step 5: Route the X2 motor cable and LED strip

Attach the **X2 motor cable** to the **X2 motor**. Then route the cable and the **LED strip** through the **horizontal cable carrier supports** along the **gantry main beam**.

![x2 motor cable and led strip routing](_images/x2_motor_cable_and_led_strip_routing.png)

# Step 6: Route all cables behind the electronics box

Route all of the cables down between the **solenoid valve mount** and the **electronics box**. You may need to temporarily disconnect the solenoid valve mount from the extrusion to facilitate fitting all of the cables in the space.

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

Connect the **vacuum pump cable** to the `VACUUM` connector on the **Farmduino Express** board.

![vacuum pump cable highlighted](_images/vacuum_pump_cable_highlighted.png)

Connect the **LED strip** to the `LIGHTING` connector on the **Farmduino Express** board.

![lighting cable highlighted](_images/lighting_cable_highlighted.png)

Connect the **X2 motor cable** to the `X2 MOTOR` connector on the **Farmduino Express** board.

![x2 motor cable highlighted](_images/x2_motor_cable_highlighted.png)

Connect the **Y motor cable** to the `Y MOTOR` connector on the **Farmduino Express** board.

![y motor cable highlighted](_images/y_motor_cable_highlighted.png)

Connect the **Z motor cable** to the `Z MOTOR` connector on the **Farmduino Express** board.

![z motor cable highlighted](_images/z_motor_cable_highlighted.png)

Connect the **camera cable** to the left microUSB connector labeled `USB` on the **Raspberry Pi Zero** board.

![camera cable cable highlighted](_images/camera_cable_cable_highlighted.png)

Connect the **power supply cable** to the red `24V POWER IN` connector on the **Farmduino Express** board.

![power cable highlighted](_images/power_cable_highlighted.png)

# Step 8: Flash FarmBot OS to the microSD card

Remove the **microSD card** from the **Raspberry Pi Zero** and follow our [FarmBot OS installation instructions](https://software.farm.bot/docs/farmbot-os#installing-farmbot-os) to install the latest version of our software. Then reinsert the microSD card into the Pi.

![microSD card in pi zero slot](_images/microsd_card_in_pi_zero_slot.png)

# Step 9: Mount the power supply

Mount the **power supply** to the **bed** using four **wood screws**. Then connect the **power supply's output** to the **power supply cable**.

![power supply mounted](_images/power_supply_mounted.png)

# Step 10: Plug FarmBot into the power source

Before plugging the power supply into an outlet or an extension cord, please read the precaution below.

{%
include callout.html
type="danger"
title="Beware of electrical shock"
content="Once you plug in the power supply, your system will be powered. Once powered, you cannot add, remove, or change any motor cables, peripheral cables, etc, or you risk frying the electronics and/or being electrically shocked.

If you need to make any changes, you must first unplug the power supply from the wall. This will minimize the risk of electrical shock and the potential to permanently damage your electronics."
%}

If everything looks good, and you understand the precautions needed around powered electronics, go ahead and plug the **power supply** into a **GFCI protected outlet**.

If an appropriate outlet is not close enough to plug in directly, use an extension cord of the appropriate length and the green **cord protector**.

{% include gallery.html images="
![power supply power connection](_images/power_supply_power_connection.png)
![power supply cord protector](_images/power_supply_cord_protector.png)
" %}

{%
include callout.html
type="success"
title="The mark of success"
content="If all has gone well, the electronics should begin booting up and you can revel in the blinking lights!"
%}

{%
include callout.html
type="warning"
title="Smell smoke or heard a loud pop?"
content="If anything seems suspicious or hazardous, **immediately unplug the power supply from the wall** and contact us at [support@farm.bot](mailto:support@farm.bot)."
%}

# What's next?

 * [Configure FarmBot](http://configure.farm.bot)
