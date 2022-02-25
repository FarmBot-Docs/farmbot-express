---
title: "Intro to FarmBot Express"
slug: "intro"
description: "95% pre-assembled, 100% open-source, plug-and-play FarmBot. [Order yours here!](http://buy.farm.bot/)"
redirect_from: /docs/v1.0/
---

* toc
{:toc}

**FarmBot Express** is designed to be an affordable and easy-to-use FarmBot for those who want to get setup and running quickly and don't need all of the features and customization options available with [FarmBot Genesis](http://genesis.farm.bot). The driving factors behind the design are simplicity, ease-of-setup, and affordability.

FarmBot Express is available in three sizes: a standard sized model suitable for small yards, greenhouses, classrooms, and research labs; an XL model suitable for families, larger spaces, multi-class school use; and a MAX model suitable for small commercial farms and large scale R&D.

|Model                         |Gantry Width                  |Length                        |Area                          |Max Plant Height              |
|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|
|Express                       |1.2m                          |3m                            |3.6m<sup>2</sup>              |0.5m
|Express XL                    |2.4m                          |6m                            |14.4m<sup>2</sup>             |0.5m

<iframe width="815" height="460" src="https://www.youtube.com/embed/0s5GU9SWquQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="815" height="460" src="https://www.youtube.com/embed/6XWiTzFPWWc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Express and Express XL share many of the same components and assembly steps. This documentation covers the assembly, bill of materials, troubleshooting tips, and more of all sized kits. When certain information only applies to one kit or the other, there will be clear indication.

# High level overview

FarmBot Express and Express XL are primarily constructed from V-Slot aluminum extrusions and aluminum plates and brackets. They are driven by four NEMA 17 stepper motors with rotary encoders, the Farmduino Express microcontroller, and a Raspberry Pi Zero computer.

{% include gallery.html images="
![FarmBot Express v1.0](_images/farmbot_express_v1.0.png)
![FarmBot Express XL v1.0](_images/farmbot_express_xl_v1.0.png)
" %}

## Tracks

FarmBot Express does not have tracks like FarmBot Genesis does. Instead, Express bots roll directly on the wood raised bed. While this doesn't provide the same level of precision as aluminum tracks do, this system is much faster to install and less expensive.

## Gantry

The **gantry** is the the structural component that bridges the long edges of the bed and allows the tool head to be moved in the X-direction. It also serves as a linear guide for the cross-slide, and a support structure for mounting the electronics box and seed tray holster.

## Cross-slide

The **cross-slide** moves in the Y-direction across the gantry. This motion provides the second major degree of freedom for FarmBot Express and allows operations such as planting to be done anywhere in the XY plane.

## Z-axis

The **Z-axis** moves through the cross-slide and provides the FarmBot with Z-direction movement. It also serves as the base for attaching the tool head, vacuum pump, and camera.

# Economies of scale

The table below shows the cost/m<sup>2</sup> of growing area based on the size of your FarmBot. Predictably, the larger your FarmBot is, the lower the cost will be per square meter of growing area. Thus, we recommend installing the largest possible FarmBot in your space in order to get the most value out of the device.

*Note that the costs below do not account for [supporting infrastructure](supporting-infrastructure.md), which will also increase in cost as the device size increases.*

|Model       |Gantry Width |Length |Growing Area      |Cost    |Cost/m^2|
|------------|-------------|-------|------------------|--------|--------|
|Express     |1.2m         |3m     |3.6m<sup>2</sup>  |~$1,800 |$500
|Express XL  |2.4m         |6m     |14.4m<sup>2</sup> |~$2,300 |$160

# Purchasing a kit

Our kits include everything you need in one box and are backed by our customer support. Your purchase goes towards improving and supporting the open-source hardware plans, software, and documentation you are reading right now.

**[Order your FarmBot here!](http://buy.farm.bot)**

<iframe width="815" height="460" src="https://www.youtube.com/embed/_jw98qozK4s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# License

Please see our [licensing page](https://meta.farm.bot/docs/licensing) to understand how our various works (hardware, software, documentation, etc) are licensed.

# What's next?

 * [Supporting Infrastructure](supporting-infrastructure.md)
