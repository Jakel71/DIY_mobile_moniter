# DIY_mobile_moniter

## What is that?

The DIY monitor is a LCD-monitor, which gets build out of an old Laptop screen, an motherboard (can be bought via Aliexpress), a controll panel, an powersupply for the backlight of the monitor and an enclosure for your new monitor. This is an guide, which explains how to build such a monitor, on what you should be careful and an example.

## Step 1: Buying the parts

It is important that your electronics are compatible, to ensure this, take your Laptop and disconnect the integrated monitor, make sure to keep the enclosure of the monitor, scince it will reduce the waste and the amount of filament which you will need. After you disconnected your monitor, turn it around so that you can see the product infos. In the example below it is "LP154WX4(TL)(E1)".

![Product info](pictures/monitor-product-info.jpg)

Go to your favorite website for buying electronics (I chose for aliexpress), then type your product information and add before you search "controller", make sure the parts you are buying include 1. connection for the backlide of your monitor (every LCD monitor funtions the same, you have to layers: 1. the Light scource and 2. a layer of crystals, which colors the pixels in the monitor); 2. a connection for the Layer of crystals; 3. some arrangement of bottons to change settings; 4. a power-source, which is compatible with the device. Here some pictures of my parts, which I bought:

![Picture of the bottons-pcb](pictures/bottons.jpg)

![Picture of the mainboard-pcb](pictures/mainboard.jpg)

![Picture of the power-pcb](pictures/power-for-the-backlight.jpg)

![Picture of the power plug for the wall](pictures/power-brick.jpg)

## Step 2: Building the monitor

When your parts arrive, you can open again your enclosure and connect your motherboard, the powersupply and the control pannel. Then close the enclosure of your monitor if possible and plug your monitor in. Test the monitor, then unplug the monitor again.

Here are some pictures, which might help you:

![Picture of the display-pins to controll the crystals](pictures/connector-display-main-board-connection-pins.jpg)
Place where to connect your mainboard to the crystals.

![Picture of the display-pcb connected to the mainboard](pictures/connector-display-main-board-connected.jpg)
The Cable plugged in.

![Picture of the cabels for the backlight](pictures/cabels-for-backlight.jpg)
Cable for the backlight of your monitor.

![Picture of the backlight-cabels connected with the power-pcb](pictures/power-to-backlight-connected.jpg)
Backlight connected with the pcb which gives the backlight enough energy.


Here are some tips for what you should watch out during your monitor building:

1. No electricity on the components, when you are working on them / don't get electricuted !!!
2. If something broke or you can't connect something permanently (besase it slips out again), tape it down, but make sure everything stays strong enough for our use-case.

![Picture of applied tape](pictures/connector-display-main-board-tapet.jpg)

## Step 3: Enclosure for the electronics

You still need an enclosure for the motherboard, powersupply and the controll panel. So get the dimensons of your platines and adjust the provided 3D-files in your favorite editor. If you are using FUSION 360, then you can use the following:

