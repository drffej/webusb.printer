WebUSB -️ Arduino Experiment
===========================

This repository is an example implementation of WebUSB communicating with Thermal Receupt printer.  It consists of a single file containing HTML and Javascript.  Demo only, no proper error checking or graphic printing.
 

The demo shows:

1. Pairing and connecting to Thermal Printer from Chrome
2. Sending prunter text to  the device from Chrome
3. Reconnecting on Browser refresh (if paired)

This works on Windows 10 hardware and on a Mac.



A. Setting Chrome for WebUSB
----------------------------

The implementation is available via the "Experimental Web Platform Features" flag.  

1. Navigate to chrome://flags
2. Enable the flag called '#enable-experimental-web-platform-features'
3. Enable the flag called '#enable-webusb'
4. Close and restart the browser

You may also want to check out  chrome://device-log where you can see all USB device related events in case of issues.

C. Access the Demo
------------------

1. Start the browser with security features disabled - e.g. "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-webusb-security
2. Plug the device into your PC/Mac and open the browser to https://drffej.github.io/webusb.arduino/
3. Click on 'Connect' to pair the device
4. Click on Toggle to turn on/off the Led


Alternately you can run this locally via

$ python -m http.server

or any other webserver and this does not need the security features disabling!

JP 24/08/2017