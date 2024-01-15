# Arduino Touch sensor + VST

By Ramin Akhavijou <br>
ramin.akhavijou@gmail.com <br>
www.akhavijou.com

This is a Max/MSP patch that gathers data from an Arduino, which reads information from a Touch Capacitive sensor. The data received in Max/MSP is utilized to trigger sounds in VST. The Arduino Touch Capacitive Shield serves as a tactile input module specifically designed for Arduino-based projects. It utilizes capacitive touch sensing technology, allowing touch-based interactions without the need for physical buttons. To integrate the Arduino Touch Capacitive Shield into a project, users connect it to their Arduino board, install the required libraries, and configure settings.

The left side of the patch is designated for receiving data in Max/MSP. This setting is configured as a default, compatible with most Arduino defaults. The Arduino script is also provided, requiring uploading to the Arduino board through the USB port. This script is a default Arduino configuration compatible with a wide range of Arduino boards. Follow these steps:
1) Connect the Arduino to the computer using the USB port.
2) Open the Arduino Script "MPR121_Touch" and upload it to the Arduino.
3) Open the Max patch "Capacitive Touch Shield_VST" and activate the toggle to receive data from the Arduino. The numeric data can be utilized for various purposes, but in this patch, it is configured to trigger sounds in VST.
