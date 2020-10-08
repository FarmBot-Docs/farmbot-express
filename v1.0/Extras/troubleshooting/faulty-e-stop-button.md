---
title: "Faulty E-Stop Button"
slug: "faulty-e-stop-button"
description: "Steps to take if the physical E-stop button on top of the electronics box is not working"
---

* toc
{:toc}

# Step 1: Check the pin binding
Navigate to the [pin bindings section](https://my.farm.bot/app/designer/settings?highlight=pin_bindings) of the settings panel and verify that you have a binding for **Button 1: E-STOP (Pi 16)** to trigger the **E-STOP** **Action**. Ensure this has been saved and synced to the FarmBot.

![Screen Shot 2020-06-12 at 8.02.42 PM.png](_images/Screen_Shot_2020-06-12_at_8.02.42_PM.png)

# Step 2: Power down FarmBot
[Shutdown FarmBot](https://my.farm.bot/app/designer/settings?highlight=shutdown_farmbot) and unplug the power.

![Screen Shot 2020-06-12 at 8.11.38 PM.png](_images/Screen_Shot_2020-06-12_at_8.11.38_PM.png)

# Step 3: Rewire the button
Unplug the **E-stop button wiring harness** from the electronics board and then the button itself. Note that the blue connector has a locking tab that must be pressed to remove the connector from the button.

![84d07bb-Estop_wiring.jpeg](_images/Estop_wiring.jpeg)

Using a small bladed screwdriver, gently lift the **tab** holding the **red wire and metal contact** into the **black plastic connector**.

![MVIMG_20200612_170431.jpg](_images/MVIMG_20200612_170431.jpg)

Gently remove the **red wire and metal contact** from the **black plastic connector**. Do NOT remove the metal contact from the wire.

![MVIMG_20200612_170504.jpg](_images/MVIMG_20200612_170504.jpg)



![MVIMG_20200612_170548.jpg](_images/MVIMG_20200612_170548.jpg)

Plug the wiring harness's blue connector back onto the button. Then plug the black connector back into the electronics board. The yellow wire should be closest to the green Raspberry Pi Zero electronics board. Then plug the red wire into the top-right pin on the electronics board.

{%
include callout.html
type="warning"
title=""
content="Ensure that the red wire's metal contact is not touching any other pins otherwise this will cause a short circuit."
%}



![MVIMG_20200612_170726.jpg](_images/MVIMG_20200612_170726.jpg)



![IMG_20200618_143443.jpg](_images/IMG_20200618_143443.jpg)

# Step 4: Power up FarmBot
Plug the FarmBot back in and wait for it to boot up. Try sending some movement commands to ensure it is fully up and running. Then test the E-stop button to ensure it works as expected.


