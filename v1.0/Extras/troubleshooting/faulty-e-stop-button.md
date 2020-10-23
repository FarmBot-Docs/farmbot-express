---
title: "Faulty E-Stop Button"
slug: "faulty-e-stop-button"
description: "Steps to take if the physical E-stop button on top of the electronics box is not working"
---

* toc
{:toc}

# Step 1: Check the pin binding
Navigate to the [pin bindings section](https://my.farm.bot/app/designer/settings?highlight=pin_bindings) of the settings panel and verify that you have a binding for **Button 1: E-STOP (Pi 16)** to trigger the **E-STOP** **Action**. Ensure this has been saved and synced to the FarmBot.

![e-stop pin binding](_images/e-stop_pin_binding.png)

# Step 2: Power down FarmBot
[Shutdown FarmBot](https://my.farm.bot/app/designer/settings?highlight=shutdown_farmbot) and unplug the power.

![shutdown button](_images/shutdown_button.png)

# Step 3: Rewire the button
Unplug the **E-stop button wiring harness** from the electronics board and then the button itself. Note that the blue connector has a locking tab that must be pressed to remove the connector from the button.

![e-stop button wiring](_images/e-stop_button_wiring.jpeg)

Using a small bladed screwdriver, gently lift the **tab** holding the **red wire and metal contact** into the **black plastic connector**.

![lift black plastic tab for red wire](_images/lift_black_plastic_tab_for_red_wire.jpg)

Gently remove the **red wire and metal contact** from the **black plastic connector**. Do NOT remove the metal contact from the wire.

{% include gallery.html images="
![remove red wire from connector](_images/remove_red_wire_from_connector.jpg)
![red wire removed from connector](_images/red_wire_removed_from_connector.jpg)
" %}

Plug the wiring harness's blue connector back onto the button. Then plug the black connector back into the electronics board. The yellow wire should be closest to the green Raspberry Pi Zero electronics board. Then plug the red wire into the top-right pin on the electronics board.

{%
include callout.html
type="warning"
title=""
content="Ensure that the red wire's metal contact is not touching any other pins otherwise this will cause a short circuit."
%}

{% include gallery.html images="
![fixed e-stop button wiring](_images/fixed_e-stop_button_wiring.jpg)
![fixed e-stop button wiring close-up](_images/fixed_e-stop_button_wiring_close-up.jpg)
" %}

# Step 4: Power up FarmBot
Plug the FarmBot back in and wait for it to boot up. Try sending some movement commands to ensure it is fully up and running. Then test the E-stop button to ensure it works as expected.


