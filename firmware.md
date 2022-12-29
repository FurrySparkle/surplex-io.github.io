---
title: Surplex Firmware
layout: home
---
# **Surplex Firmware**
---


This doc will guide you through downloading and uploading firmware to your Surplex's Shoes.

Our firmware is developed on the platform of Arduino.

Please go through the following steps:

1. Download Firmware Zip through our firmware [repository].

2. Go to Arduino IDE (If you have installed) or Arduino [Cloud Editor] and open the firmware file.

3. Change the SECRET to your own information as follow:

   ![secret](assets/secret.png)

4. Upload firmware to the left shoe with default metadata as follow:
   
   ![left](assets/left.png)

5. Comment out left metadata and upload firmware to the right shoes with the following setup:

   ![right](assets/right.png)


Once you have uploaded the firmware, please head over to Surplex's [Driver] site and download Surplex's OpenVR driver for communicating between Surplex's shoes and VR headsets.


[repository]: https://github.com/surplex-io/surplex_firmware/
[Cloud Editor]: https://create.arduino.cc/editor/
[Driver]: ../driver.html