---
description: Understanding how the sensor reads and sends data
---

# Sensor Readings - R3

For most of the time, the R3 tank level sensor will be in **sleep mode**. This means that it is unreachable from the app, and it cannot be seen on your WiFi network. This is a power saving mechanism. The R3 sensor will only "**wake up**" and send an updated level reading in the following cases:

* **Scheduled wake up** - every 12 hours by default. This can be changed by adjusting the "**Reading Frequency**" in the app under Settings > Sensor / Tank Settings
  * NOTE: any changes to the "Reading Frequency" will only come into affect **the next time a sensor goes online**
  * To get readings at a certain time (e.g. 11am / 11pm), use one of the methods below to wake the sensor at the time you want.  This will restart the onboard timer.
* **Button press** - unscrew the unit to access the base of the sensor. Press the button once. When the beeping starts (10 second timer) - put the sensor back down in place on the tank
* **Magnet swipe** - the sensor comes with a blue magnet. **Hold the magnet** in the position shown for **at least 6 seconds**. After moving the magnet away - a single **beep** will be heard. This restarts the sensor, and will trigger another reading &#x20;

There is usually a slight delay from the time a sensor sends a reading, to when it is visible in the app. To check your data, go to the **dashboard screen** of the TankMate app and **swipe down** (in the center of the screen) - this will **refresh the app data**. Check the last reading date / time.&#x20;

![](../../../.gitbook/assets/20220329\_134955.jpg)
