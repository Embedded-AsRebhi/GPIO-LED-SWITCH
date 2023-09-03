# GPIO-LED-SWITCH
The objective of this subproject is to control both internal and external  LEDs using a push-button.

To control the internal LEDs, you need to configure them as inputs and the push-button as an output. To do this, right-click in the box corresponding to the appropriate pin.
For instance, to set the blue button PB1 as an input, you should define the box for PA0 as "GPIO_Input" in the selection menu.
Initially, we implemented an example of a light sequence where the internal LEDs light up cyclically when the push-button is pressed and turn off when the button is released.
