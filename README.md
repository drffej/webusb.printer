WebUSB - Arduino Experiment
===========================

This repository is an example implementation of WebUSB communicating with Thermal Receupt printer.  It consists of a single file containing HTML and Javascript.  Demo only, no proper error checking or graphic printing.
 

The demo shows:

1. Pairing and connecting to Thermal Printer from Chrome
2. Sending printer text to  the device from Chrome
3. Reconnecting on Browser refresh (if paired)

This has been tested on Windows 10 hardware and on a Mac.

Access the Demo
---------------

1. Plug the device into your PC/Mac and open the browser to https://drffej.github.io/webusb.printer/printer.html
2. Click on 'Connect' to pair the device
3. Click on Toggle to turn on/off the Led


Alternately you can run this locally via

$ python -m http.server

or any other webserver.

You may also want to check out  chrome://device-log where you can see all USB device related events in case of issues.

JP 26/11/2017
