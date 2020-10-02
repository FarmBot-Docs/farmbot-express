---
title: "Plug Everything In"
slug: "plug-everything-in"
---

* toc
{:toc}


{%
include callout.html
type="warning"
title="Power should still be disconnected"
content="At this time, the FarmBot should not be plugged into any power source."
%}

# Step 1: Connect the Y motor
Route the **Y motor cable** through the slot in the **cross-slide plate** and connect it to the **Y motor**.

![Screen Shot 2019-12-18 at 12.25.08 PM.png](Screen_Shot_2019-12-18_at_12.25.08_PM.png)

# Step 2: Connect the water tubes
Connect the **water tube** coming from the **y-axis cable carrier** to the **90 degree barb**.

![Screen Shot 2019-12-18 at 12.26.47 PM.png](Screen_Shot_2019-12-18_at_12.26.47_PM.png)

Connect the other end of the **water tube** coming from the **y-axis cable carrier** to the **barbed adapter** above the **solenoid valve**.

![Screen Shot 2019-12-18 at 12.38.11 PM.png](Screen_Shot_2019-12-18_at_12.38.11_PM.png)

Connect the **water tube** coming from the top of the **x-axis cable carrier** to the **barbed adapter** below the **solenoid valve**.

![Screen Shot 2019-12-18 at 2.43.37 PM.png](Screen_Shot_2019-12-18_at_2.43.37_PM.png)

Screw the **garden hose to barb adapter** onto a **garden hose** of the appropriate length. Then connect the **water tube** coming from the bottom of the **x-axis cable carrier** to the **garden hose to barb adapter**.

![Screen Shot 2019-12-18 at 3.14.18 PM.png](Screen_Shot_2019-12-18_at_3.14.18_PM.png)

# Step 3: Check for leaks
Turn on the supply of water at your **garden hose spigot** and check the FarmBot for any leaks. If your municipal water pressure is abnormally high, you may need to add **zip-ties** to the tube-to-barb connections to prevent the tubes from popping off. In rare circumstances you also may need to add plumber's tape (teflon tape) to the threaded connections at the hose or solenoid valve to prevent leaking.

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



![Screen Shot 2019-12-18 at 12.31.34 PM.png](Screen_Shot_2019-12-18_at_12.31.34_PM.png)

Pay special attention that you fully insert the 90-degree connectors together. This may require a multi-step process of pushing together, slightly tightening the thumb screws, pushing together again, and tightening some more. See the video below for detail.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FrPqgmoE3PbI%3Ffeature%3Doembed&display_name=YouTube&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DrPqgmoE3PbI&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FrPqgmoE3PbI%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" title="YouTube embed" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>

# Step 5: Route the X2 motor cable and LED strip
Attach the **X2 motor cable** to the **X2 motor**. Then route the cable and the **LED strip** through the **horizontal cable carrier supports** along the **gantry main beam**.

![Screen Shot 2019-12-18 at 11.52.34 AM.png](Screen_Shot_2019-12-18_at_11.52.34_AM.png)

# Step 6: Route all cables behind the electronics box
Route all of the cables down between the **solenoid valve mount** and the **electronics box**. You may need to temporarily disconnect the solenoid valve mount from the extrusion to facilitate fitting all of the cables in the space.

![Screen Shot 2019-12-18 at 12.36.24 PM.png](Screen_Shot_2019-12-18_at_12.36.24_PM.png)

# Step 7: Plug everything in

{%
include callout.html
type="danger"
title="Power should still be disconnected"
content="At this time, the FarmBot should not be plugged into any power source."
%}

Connect the **vacuum pump cable** to the `VACUUM` connector on the **Farmduino Express** board.

![Screen Shot 2019-12-18 at 12.41.31 PM.png](Screen_Shot_2019-12-18_at_12.41.31_PM.png)

Connect the **LED strip** to the `LIGHTING` connector on the **Farmduino Express** board.

![Screen Shot 2019-12-18 at 11.33.53 AM.png](Screen_Shot_2019-12-18_at_11.33.53_AM.png)

Connect the **X2 motor cable** to the `X2 MOTOR` connector on the **Farmduino Express** board.

![Screen Shot 2019-12-18 at 11.33.41 AM.png](Screen_Shot_2019-12-18_at_11.33.41_AM.png)

Connect the **Y motor cable** to the `Y MOTOR` connector on the **Farmduino Express** board.

![Screen Shot 2019-12-18 at 12.41.05 PM.png](Screen_Shot_2019-12-18_at_12.41.05_PM.png)

Connect the **Z motor cable** to the `Z MOTOR` connector on the **Farmduino Express** board.

![Screen Shot 2019-12-18 at 12.41.12 PM.png](Screen_Shot_2019-12-18_at_12.41.12_PM.png)

Connect the **camera cable** to the left microUSB connector labeled `USB` on the **Raspberry Pi Zero** board.

![Screen Shot 2019-12-18 at 12.40.47 PM.png](Screen_Shot_2019-12-18_at_12.40.47_PM.png)

Connect the **power supply cable** to the red `24V POWER IN` connector on the **Farmduino Express** board.

![Screen Shot 2019-12-18 at 2.54.47 PM.png](Screen_Shot_2019-12-18_at_2.54.47_PM.png)

# Step 8: Flash FarmBot OS to the microSD card
Remove the **microSD card** from the **Raspberry Pi Zero** and follow our [FarmBot OS installation instructions](https://software.farm.bot/docs/farmbot-os#installing-farmbot-os) to install the latest version of our software. Then reinsert the microSD card into the Pi.

![Screen Shot 2020-01-30 at 1.29.47 PM.png](Screen_Shot_2020-01-30_at_1.29.47_PM.png)

# Step 9: Mount the power supply
Mount the **power supply** to the **bed** using four **wood screws**. Then connect the **power supply's output** to the **power supply cable**.

![Screen Shot 2019-12-18 at 3.19.07 PM.png](Screen_Shot_2019-12-18_at_3.19.07_PM.png)

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

![Screen Shot 2019-12-18 at 2.36.40 PM.png](Screen_Shot_2019-12-18_at_2.36.40_PM.png)



![Screen Shot 2019-12-18 at 2.37.41 PM.png](Screen_Shot_2019-12-18_at_2.37.41_PM.png)



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



<style>
.hub-container {
  max-width: 1350px;
}

h1 {
  font-family: Inknut Antiqua;
}
  
a[title="Guides"] {
  color: #f4f4f4!important;
  border-bottom: 5px solid #f4f4f4;
  padding-bottom: 20px!important;
}
  
a[title="Guides"]:hover {
  color: white!important;
  border-bottom-color: white;
}
  
#hub-header li a:hover {
  box-shadow: none!important;
}
</style>

<meta name="theme-color" content="#942401">


# What's next?

 * [Configure FarmBot](http://configure.farm.bot)
