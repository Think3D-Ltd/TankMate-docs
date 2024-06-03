---
description: >-
  Tips for troubleshooting a TankMate Wi-Fi connection - for TankMate v2 or R3W
  models
---

# Check Connectivity - v2 and R3W WiFi Sensors

### Check the status of the WiFi sensor unit

Use the **WAKE / RESET** button on the **side** (v2) or **base** (R3) of the unit to see the current connectivity status:

{% hint style="warning" %}
Click the **WAKE / RESET** button briefly to wake the unit!&#x20;

Holding this button down longer than a few seconds will clear the Wi-Fi credentials. &#x20;
{% endhint %}

### Status LED Modes Explained - WiFi Sensors

* **No LED** light = **low battery** / power issue. See battery replacement section for [v2 sensors](../tankmate-user-guide/tankmate-wifi-sensors/tankmate-v2-wifi-sensors/v2-battery-replacement.md), or [R3 sensors](../tankmate-user-guide/tankmate-wifi-sensors/tankmate-r3-wifi-sensors/r3-battery-replacement.md)
* Blinking green, then **solid LIGHT BLUE** (CYAN) for **5-10 seconds** <img src="../.gitbook/assets/wifi_connect.gif" alt="" data-size="line">= the unit is already connected to a Wi-Fi network
* **Solid LIGHT BLUE** (CYAN) for **60+ seconds, but no data transmitted** = the unit is connected to a Wi-Fi network, but cannot send data. It may need a manual firmware update. [See here for details](firmware-update-august-2023.md).
* Blinking green for 10-15 seconds, then **blinking RED** <img src="../.gitbook/assets/connect_failed.gif" alt="" data-size="line"> = failed connection. See possible causes below
* **Continuous blinking** BLUE or PURPLE <img src="../.gitbook/assets/blueconnect.gif" alt="" data-size="line"> = not connected / waiting for WiFi credentials from the app. The the "Reconnect" page for details

### Troubleshooting a failed connection

If a sensor that was previously connected, no longer connects to the network:&#x20;

* **Power cycle your router / modem**. Unplug for 30 seconds, then power it back up. After waiting for the Wi-Fi network to turn on (1-2 mins), test the connection as above.
* Has your **network name (SSID) or password been changed** since the TankMate sensor was set up? If so, reconnect the sensor using the updated details.
* Check that the **sensor firmware** is up-to-date - [see here](firmware-update-august-2023.md).&#x20;

{% hint style="info" %}
TIP: use a phone or tablet to troubleshoot issues with a Wi-Fi password. Under your network settings, FORGET the selected network, and then connect again using your password.&#x20;
{% endhint %}

{% hint style="warning" %}
NOTE: WiFi passwords that include the $ symbol are not currently supported by TankMate sensors. We recommend modifying the password, or setting up a guest network with a different password.
{% endhint %}

**Advanced wireless settings / firewall issues:**

* Note that TankMate sensors can only connect to **2.4GHz** networks. Combined 2.4 / 5GHz networks are also supported
* Certain networks may apply restrictions that limit network access for smart devices. Check your network security settings / advanced wireless settings in this case, or contact your service provider to troubleshoot the issue.
* In some cases, setting up a **guest network** (2.4GHz) can be a good workaround for advanced network settings
* The TankMate Wi-Fi sensor uses **port 8883** to send data to the internet - ensure this is not restricted
