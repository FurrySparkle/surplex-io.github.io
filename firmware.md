---
title: Surplex Firmware
layout: home
---

This doc will guide you through download and upload firmware to your Surplex's Shoes.

Our firmware are developed on the platform of Arduino.

Please go through following steps:

1. Download Firmware Zip through our firmware [repository].

2. Go to Arduino IDE or Arduino [Cloud Editor] and open the firmware file.

3. Change the SECRET to your own information as follow:

   ![secret](assets/secret.png)

4. Upload firmware to the left shoe with default metadata as follow:
   
   ![left](assets/left.png)

5. Comment out left metadata and upload firmware to right shoes with following setup:

   ![right](assets/right.png)


Once you have the firmware uploaded. Please head over to Surplex's [Driver] site and download Surplex's OpenVR driver for communicating between Surplex's shoes and VR headsets.


----

[repository]: https://github.com/surplex-io/surplex_firmware/
[Cloud Editor]: https://create.arduino.cc/editor/
[Driver]: ../driver.html