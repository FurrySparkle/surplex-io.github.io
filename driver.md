---
title: SteamVR Driver
layout: home
---
# **OpenVR Driver**
---

This doc will guide you through setting up Open-VR Driver required for communication between VR headsets and Surplex's shoes. Our driver is [open-source] on Github.

Our OpenVR Driver is developed based on John Dean's previous open-source VR tracker [driver]. It used WebSocket to communicate between trackers and OpenVR. As a pre-requisite, you must download [OpenSSL] and install it on your computer if you haven't done so before.

Then, you can install it by: Download the [driver file] and moving the `websocket_trackers` directory into the SteamVR driver's directory, which should be located somewhere at: 
````
C:\Program Files (x86)\Steam\steamapps\common\SteamVR\drivers
````

Once you have done the steps above, please head over to Surplex [software] page for the final steps required before using Surplex's shoes!

[driver]: https://github.com/John-Dean/OpenVR-Tracker-Websocket-Driver
[OpenSSL]: https://slproweb.com/products/Win32OpenSSL.html 
[driver file]: https://github.com/John-Dean/OpenVR-Tracker-Websocket-Driver/releases/latest/download/driver.zip
[software]: ../software.html
[open-source]: https://github.com/surplex-io/OpenVR-Driver/