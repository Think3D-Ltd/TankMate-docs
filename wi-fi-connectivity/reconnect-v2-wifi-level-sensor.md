---
description: >-
  The app has two methods to reconnect a v2 sensor to a WiFi network. The
  default mode is called BlueConnect, which uses a temporary bluetooth
  connection to send network credentials to the sensor.
cover: ../.gitbook/assets/DSCF8788_1024.jpg
coverY: 0
---

# Reconnect - v2 WiFi Level Sensor

{% hint style="success" %}
First, check that your sensor is not already connected! Press the **RESET button once** (short press) and watch the **status LED**. If you see a **solid BLUE (cyan)** colour for **5-10 seconds**, the unit is already **connected** to the network
{% endhint %}

### Reconnect a sensor using BlueConnect

* In the TankMate app, go to **Settings** > **Sensor / Tank Settings** > **Edit Network Settings**
* Put the sensor into BlueConnect mode: on the side of the sender unit - hold the **RESET** button for **6-8 seconds** then release.
* The status LED will **blink slowly** - **dark blue** - when in BlueConnect mode <img src="../.gitbook/assets/blueconnect.gif" alt="" data-size="line">
* The unit will go to sleep to conserve power after 3 mins. Click RESET again to wake it up.
* Follow the prompts in the app. Further details on the [BlueConnect process can be found here](using-bluconnect.md).

{% hint style="warning" %}
**NOTE:** as of November 2023, all v2 sensors **must** be running **firmware version 21 or above**. Sensors running an older firmware version will not be able to send data to the TankMate server - and will need to be manually updated. Contact us for details.

The firmware version no. can be seen on the (expanded) home screen of the app.
{% endhint %}

{% hint style="danger" %}
**NOTE:** WiFi passwords that include the **$ symbol** are not currently supported by some older TankMate sensors. We recommend modifying the password, or setting up a guest network with a different password.
{% endhint %}



<figure><img src="../.gitbook/assets/Screen Shot 2023-12-20 at 7.36.01 AM.png" alt=""><figcaption><p>Edit the network settings for an existing sensor</p></figcaption></figure>
