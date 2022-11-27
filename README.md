# KeyMaster5000

## Intro
The Keymaster5000 aims to be the most over the top, feature packed keybaord in existance.  Why you may ask? Well, because I can....

## Features
- Modular Design
  - Display Module (8 keys and Touch Strip)
  - Numberpad Module (17 Key full Numpad and 4 Function Keys)
  - Core Module (84 Keys, 13 Function Keys and 3 Device Selector Keys)
- Small full HD multitouch display for GIF Selection and keyboard confiiration
- USB 3.0 Hub when USB is plugged in
- 2 USB-C ports for downstream devices
- 1 USB-A port for downstram devices
- Huge Battery Capacity
- Bluetooth 5.3 connectivity
- Low latency 2.4 GHz Connectivity with dongle
- Force feeback capable smart knob with OLED display
- Removable switches using MilMax Contacts
- Modules are all independantly powered and able to communicate with each other wirelessly when not connected
- Sub 1ms switch press latency when running on USB
- RGB LEDs for every key
- Wireless Audio integrated into keyboard with 3.5mm Jack
- Proximity sensing for "Smart wakeup"
- Ambient Light sensing for automatic brightness adjustment
- Assignable Touch sensitive strip on Numberpad and Core Module

## Display Module
This is where we get clever.  The display module integrates a multitouch display, a smart display knob, based off of the [design from Scott Bezek](https://github.com/scottbez1/smartknob) with a couple of tweaks, a quad core [TI AM625](https://www.ti.com/product/AM625) to run the displays and other computationally intense tasks and a dual core [Nordic Semi nRF5340](https://www.nordicsemi.com/products/nrf5340) to handle all the wireless tasks.
This module includes two 18650 3500mAh Cells for power, and can be charged over USB, or when connected to the Core.

## Numberpad Module
This Module is probably the most boring, just a full size number pad with four function keys and a touch strip down the side. It is based off of a dual core [Nordic Semi nRF5340](https://www.nordicsemi.com/products/nrf5340). The use of level shift registers allows the entire keyboard to be laid out in a 1 by 21 matrix, with a scan rate based on that of the clock speed.
This module includes two 18650 3500mAh Cells for power, and can be charged over USB, or when connected to the Core.

## Core Module
This is the heart of Keymaster, it is based off of a dual core [Nordic Semi nRF5340](https://www.nordicsemi.com/products/nrf5340). The use of level shift registers allows the entire keyboard to be laid out in a 1 by 100 matrix, with a scan rate based on that of the clock speed, meaning the entire keyboard can be read at speeds up to 12.5MHz, but, assuming a clock speed of 1MHz results in all 100 keys being read every 0.1ms.  Speedy huh?
This module includes six 18650 3500mAh Cells for power, and can be charged over USB and can charge the display and Numberpad modules when connected together.
As for the key layout, the keyboard uses a full size layout with arrow keys and three switches to allow fast switcing between devices, meaning you can pair your keyboard with 3 PCs and then instantly have all the modules switch from one device to the next.  It also includes a touch strip at the base of the keyboard to do whatever you want really.
