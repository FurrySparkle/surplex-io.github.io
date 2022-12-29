---
title: SteamVR Driver
layout: home
---

This doc will guide you through setting up Open-VR Driver required for communication between VR headsets and Surplex's shoes.

Our OpenVR Driver is developed based on John Dean's previous open-source VR tracker [driver]. It used WebSocket to communicate between trackers and OpenVR. As a pre-requisite, you must download [OpenSSL] and install it on your computer if you haven't done so before.

Then, you can install it through: Download the [driver file] and move the `websocket_trackers` directory into the SteamVR drivers directory, which should be located somewhere at: 
````
C:\Program Files (x86)\Steam\steamapps\common\SteamVR\drivers
````

Once you have done the steps above, please head over to Surplex [software] page for the final steps required before using the Surplex's shoes!

----
[driver]: https://github.com/John-Dean/OpenVR-Tracker-Websocket-Driver
[OpenSSL]: https://slproweb.com/products/Win32OpenSSL.html 
[driver file]: https://github.com/John-Dean/OpenVR-Tracker-Websocket-Driver/releases/latest/download/driver.zip
[software]: ../software.html