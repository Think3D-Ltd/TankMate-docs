---
description: Installation guide for TankMate R3 sensors
---

# Set Up a New R3 Sensor

{% file src="../../../../.gitbook/assets/TMR3-quickstartguide-April-2023.pdf" %}
See the Quick Start Guide pdf
{% endfile %}

## Add a New Sensor

### Using BlueConnect

* In the TankMate app, select **R3** - on the "Add New Sensor" screen&#x20;
* Scan the **QR code** - located under the base of the sensor
* Ensure the sensor is in **BlueConnect mode** - the status LED will **blink dark blue (slowly)** - when in this mode <img src="../../../../.gitbook/assets/blueconnect.gif" alt="" data-size="line">

{% hint style="info" %}
The sensor will **go to sleep after 3 minutes** of inactivity. To get it back into BluConnect mode, press the **READ / RESET** button once, to wake it up
{% endhint %}

* Follow the prompts in the app to initiate a **temporary bluetooth connection.** This will only last until the sensor has been **connected to the WiFi network**
* A **success message** will be displayed after the sensor has connected to the app

On the next screen:

* Select the correct **WiFi network (SSID)** and **enter the password**
* Ensure **the sensor is still blinking** dark blue&#x20;
* Press "**CONFIRM**" to send your network details to the sensor

![Setting the WiFi credentials](../../../../.gitbook/assets/select\_ssid.jpg)

{% hint style="success" %}
A **success message** should be displayed in the app - to indicate a successful connection! Continue through the next few screens to set the tank dimensions.
{% endhint %}

{% hint style="info" %}
**No SSID listed in the app?** This may happen when:

* the phone is not connected to a WiFi network
* **location services** have **not been enabled** for the app - [see here](../../../../wi-fi-connectivity/enabling-location-services.md)&#x20;
{% endhint %}

{% hint style="info" %}
Note: The **sensor** should be **within a few metres of your mobile phone** - to ensure the temporary bluetooth connection is still in range
{% endhint %}

{% hint style="danger" %}
For toubleshooting issues with BluConnect - [see here](../../../../wi-fi-connectivity/using-bluconnect.md)
{% endhint %}
