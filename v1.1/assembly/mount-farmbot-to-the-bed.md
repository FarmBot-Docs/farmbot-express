---
title: "Mount FarmBot to the Bed"
slug: "mount-farmbot-to-the-bed"
---

# Step 1: Route the belts

Feed each end of the x-axis [[belts]] down through the center channels in the two [[gantry columns]]. Then route the belts under the [[idler pulleys]]. Ensure there are no twists inside the extrusions. The belt teeth should be facing down towards the bed.

{% include gallery.html images="
![x axis belt pulley routing](_images/x_axis_belt_pulley_routing.png)
![x axis belt idler pulley routing](_images/x_axis_belt_idler_pulley_routing.png)
" %}

# Step 2: Secure the belts

Secure both ends of each [[belt]] to a [[belt clip]] using a [[belt sleeve]] and the same method used when [securing the y-axis belt](attach-the-z-axis.md#step-3-attach-the-y-axis-belt). Then attach the belt clips to the **raised bed** using two [[wood screws]]. The belt clip tabs should be extending over the outside of the bed to serve as hardstops against the gantry wheel plates.

{%
include callout.html
type="success"
title="Just like tying your shoes"
content="When tightening and securing the belts and belt clips, use the same amount of force you would use to tie your shoes. There should be no slack in the system once the belt sleeve is in place."
%}

{%
include callout.html
type="warning"
title="Do not overtighten"
content="Overtightening the belts may result in the front wheels of the gantry lifting off of the raised bed. If you notice this, loosen the belts slightly so that the gantry rests and rolls on the bed with all four wheels."
%}

{% include gallery.html images="
![x axis belt clip mounted](_images/x_axis_belt_clip_mounted.png)
![x axis belt clip mounted 2](_images/x_axis_belt_clip_mounted_2.png)
" %}

# Step 3: Attach the x-axis cable carrier

Lay the **loaded x-axis cable carrier** onto the bed's **cable carrier support**. Fasten it to the bed with two [[wood screws]] and to the **cable carrier mount** with two [[M3 x 16mm flat head screws]] and [[M3 locknuts]].

{% include gallery.html images="
![x axis cable carrier overview](_images/x_axis_cable_carrier_overview.png)
![x axis cable carrier mounting screws](_images/x_axis_cable_carrier_mounting_screws.png)
![x axis cable carrier gantry mount](_images/x_axis_cable_carrier_gantry_mount.png)
" %}

# Step 4: Equalize the gantry

{%
include callout.html
type="info"
content="An **equalized gantry** is one that is exactly _perpendicular_ to the long edges of the wood raised bed that FarmBot runs along.

A crooked or torqued gantry can cause creaking, extra wear, and introduce a high amount of friction into the system that might result in motor stalls. It also just looks bad."
%}

To equalize the gantry, first ensure that the x-axis motors are unpowered. For first time installation this will always be the case because we haven't yet plugged everything in!

Gently push or pull on the gantry **from the middle of the gantry main beam** such that it moves slowly along the raised bed about 30cm. This process will remove any torque on the gantry, and ensure it is not crooked. If you push or pull the gantry from one of the gantry columns, or anywhere that is not the middle of the main beam, then you will torque the gantry and make it crooked. _Don't do that!_

{%
include callout.html
type="home"
content="If you were equalizing the gantry as part of routine maintenance, remember to <span class='fb-button fb-yellow'>FIND HOME X</span> after equalization."
%}

# What's next?

 * [Plug Everything In](plug-everything-in.md)
