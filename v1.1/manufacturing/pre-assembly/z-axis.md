---
title: "Z-Axis"
slug: "z-axis"
description: "Pre-assembly instructions for the FarmBot Express and Express XL Z-axis"
---


![z axis](_images/z_axis.png)

# Component list

|Component                                   |Qty |
|--------------------------------------------|----|
|[[Z-Axis Extrusion]]                        |1
|[[Vertical Motor Mount]]                    |1
|[[NEMA 17 Motor]]                           |1
|[[50mm Vertical Motor Housing]]             |1
|[[5mm to 8mm Shaft Coupler]]                |1
|[[Leadscrew]]                               |1
|[[40mm Vertical Cable Carrier Support]]     |4
|[[Loaded Z-Axis Cable Carrier Subassembly]] |1
|[[Vacuum Pump Mount]]                       |1
|[[Vacuum Pump]]                             |1
|[[Vacuum Pump Housing]]                     |1
|[[Vacuum Tube]]                             |2
|[[Inline Vacuum Pump Filter]]               |1
|[[M5 x 16mm Screw]]                         |2
|[[M5 x 10mm Screw]]                         |14
|[[M3 x 12mm Screw]]                         |4
|[[60mm Nut Bar]]                            |3
|[[40mm Nut Bar]]                            |4
|[[10mm Nut Bar]]                            |2
|[[200mm Zip Tie]]                           |2

# Step 1: Mount the vacuum pump

Attach the [[vacuum pump mount]] to the the [[z-axis extrusion]] using two [[M5 x 16mm screws]] and one [[60mm nut bar]]. The bottom of the mount should be 185mm from the bottom of the extrusion.

![z axis extrusion with vacuum pump mount](_images/z_axis_extrusion_with_vacuum_pump_mount.png)

Securely tighten the [[vacuum pump]] onto the [[vacuum pump mount]] using two [[200mm zip ties]]. Cut off the excess zip tie material.

![vacuum pump on mount closeup](_images/vacuum_pump_on_mount_closeup.png)

Press one of the **vacuum tubes** onto the **inlet** of the [[vacuum pump]]. Then press the **inline filter** onto the open end of the tube. Then press the second vacuum tube onto the open end of the inline filter.

{% include gallery.html images="
![vacuum pump inlet](_images/vacuum_tube_assembly_inlet_detail.png)
![vacuum tube assembly](_images/vacuum_tube_assembly.png)
" %}

Attach the [[vacuum pump housing]] to the [[z-axis extrusion]] using two [[M5 x 10mm screws]] and [[10mm nut bars]].

![vacuum pump housing](_images/vacuum_pump_housing.png)

# Step 2: Mount the cable carrier supports

Attach the four **40mm vertical cable carrier supports** to the [[z-axis extrusion]] using [[M5 x 10mm screws]] and [[40mm nut bars]]. The space between all supports should be 180mm.

![mount z-axis cable carrier supports](_images/mount_z-axis_cable_carrier_supports.png)

# Step 3: Mount the motor

Attach the **z-axis motor mount** to the [[z-axis extrusion]] using two [[M5 x 10mm screws]] and one [[60mm nut bar]]. The recessed lip of the motor mount should be 60mm from the top of the extrusion.

![z axis motor mount](_images/z_axis_motor_mount.png)

Position the [[motor]] on the mount with the motor's connector facing the extrusion. Then secure the motor in place with four [[M3 x 12mm screws]].

![z axis motor](_images/z_axis_motor.png)

{%
include callout.html
type="danger"
title=""
content="The following step requires the [z-axis cable carrier to be loaded with cables and tubing](cable-carriers.md) before installing in the z-axis. Do not proceed unless you have the cable carrier loaded."
%}

# Step 4: Mount the cable carrier

Position the **loaded z-axis cable carrier** in the **cable carrier supports** such that the camera is located at the bottom of the extrusion. Secure the cable carrier to the **vertical cable carrier support** using two [[M5 x 16mm screws]] and [[M5 flange locknuts]].

{% include gallery.html images="
![z axis with cable carrier](_images/z_axis_with_cable_carrier.png)
![z axis with cable carrier end closeup](_images/z_axis_with_cable_carrier_end_closeup.png)
" %}

_Note: not all cables are shown_

# Step 5: Connect the z-axis motor cable

Feed the **z-axis motor cable** up through the slots in the four **cable carrier supports** and the slot in the **z-axis motor mount**. Then plug the cable into the [[motor]].

![z axis with motor cable highlighted](_images/z_axis_with_motor_cable_highlighted.png)

# Step 6: Connect the vacuum pump cable

Feed the [[vacuum pump cable]] up through the slot in the first **cable carrier support** and then plug the connectors into the **vacuum pump's terminals**.

# Step 7: Mount the motor housing

Mount the **50mm vertical motor housing** using two [[M5 x 10mm screws]] and one [[60mm nut bar]]. The housing should fit snugly in the motor mount's recessed lip. The top of the motor housing should also be flush with the top of the extrusion, which may require a slight adjustment of the motor mount's position.

![z axis with motor housing closeup](_images/z_axis_with_motor_housing_closeup.png)

# Step 8: Attach the leadscrew

Insert the [[leadscrew]] fully into the [[shaft coupler]] and tighten the setscrews.

![z axis leadscrew with shaft coupler](_images/z_axis_leadscrew_with_shaft_coupler.png)

Slide the [[shaft coupler]] onto the **motor shaft**, ensuring that the setscrews are aligned with the flat sides of the motor shaft. Ensure there is approximately 1-3mm of space between the end of the motor shaft and the end of the leadscrew - they should **not** be touching inside the coupler. Tighten the setscrews.

![z axis with leadscrew](_images/z_axis_with_leadscrew.png)
