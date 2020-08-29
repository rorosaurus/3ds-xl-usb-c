# 3ds-xl-usb-c
A USB-C mod for the 3DS XL!

# Instructions

## A note on the charging dock contacts

I recommend abandoning the charging dock contacts if you install this mod. The USB-C port is ~8.8mm wide, the charging dock contacts are ~9.8mm apart. That means, properly centered, you'd have 0.5mm of plastic/prayers in-between your 5V dock contact and the grounded USB-C port frame. I personally don't want to deal with that likely short-circuit, but it might technically be possible if you are super careful and passionate about keeping the charging dock contacts. Make sure you harvest the contacts as you remove the standard charging port, and you'll need to modify the 3D printed bezel to accommodate those charging contacts.

## Step 1: Disassemble your 3DS XL and remove the motherboard

You can follow [this iFixit guide](https://www.ifixit.com/Guide/Nintendo+3DS+XL+Motherboard+Replacement/25399) for good disassembly instructions.

## Step 2: Remove the existing charge port

IMO, this is the hardest part by far. I found it easiest to solder-suck / wick the charging dock contacts first, then remove them.

![Removing charging dock contacts](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/removing-charging-dock-contacts.jpg)

Then I broke off and removed the charging dock contacts plastic support.

![Removing charging dock plastic](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/removing-charging-dock-plastic.jpg)

Then I was able to solder-suck / wick the charging port itself and remove it. I should have been more patient to avoid damaging the pads a little bit.

![Removed charging port](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/removed-charging-port.jpg)

## Step 3: Prepare the new charge port

Assemble (and test!) the new USB-C charge port. That means positioning and soldering the brace into the perfect place, and adding the USB-C port and resistors if your mod came unassembled.

![Unassembled PCB](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/unassembled-pcb.jpg)

Add some solder to sandwich the brace and the main PCB, lining the brace up flat with the edge of the main PCB, like this:

![Assembled PCB bottom](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/assembled-pcb-bottom.jpg)

Ensure it fits well into the slot left by the old charging port.

![Assembled PCB bottom alignment](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/assembled-pcb-bottom-alignment.jpg)

Add your USB-C port and resistors if they aren't there already.

![Assembled PCB top](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/assembled-pcb-top.jpg)

Ensure that your USB-C PCB and the motherboard are flat and flush before continuing.

## Step 4: Position and attach the new charge port

It should align like this, with holes lining up with the motherboard pads underneath.

![Assembled PCB top alignment](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/assembled-pcb-top-alignment.jpg)

Solder each hole, ensuring you heat up the pad underneath and allow solder to flow into the hole, securing the USB-C PCB to the motherboard at each of the 4 holes. Then finally use solder to attach the final half-circle pad to the 5V motherboard pad beneath it.

![New charging port attached](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/new-charging-port-attached.jpg)

## Step 5: Case trimming

Use a dremel, sandpaper, and flush cutters to trim the case to fit the new port width. In my case, I chose to absorb the charging dock contacts as well, then fill it in with a 3D printed bezel.

![After no bezel](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/after-no-bezel.jpg)

## Step 6: 3D Print bezel to fill the gap

https://github.com/rorosaurus/3ds-xl-usb-c#3d-printable-bezel

![After with bezel](https://github.com/rorosaurus/3ds-xl-usb-c/blob/master/images/after-with-bezel.jpg)