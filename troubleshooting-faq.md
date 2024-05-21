---
description: Frequently asked questions
---

# Troubleshooting - FAQ

### New Sensors - Setup Issues

For assistance with setting up a new [R3 sensor see here](tankmate-user-guide/tankmate-wifi-sensors/tankmate-r3-wifi-sensors/set-up-a-new-r3-sensor/)&#x20;

### Existing Sensors - Connectivity

<details>

<summary>My app has not show any updated readings for a while. What should I do?</summary>

On the main dashboard screen of the app - swipe down to refresh the data. If the **last reading date/time** was more than 24 hours ago, you may need to [check the sensor unit](wi-fi-connectivity/check-connectivity-v2-and-r3w-wifi-sensors.md) or the network connection. Common causes include:

* An issue with the **WiFi network** (router turned off, new network name / password)&#x20;
* Low battery on the sensor
* WiFi credentials cleared / lost

</details>

<details>

<summary>I have a new router / or WiFi password. How can I get my sensor back online?</summary>

See links below for reconnecting a TankMate product to a network:

* [R3 Sensor](wi-fi-connectivity/reconnect-r3-wi-fi-level-sensor.md)
* [v2 Sensor](wi-fi-connectivity/reconnect-v2-wi-fi-level-sensor.md)
* [v1 Sensor](wi-fi-connectivity/reconnect-v1-level-sensor.md)

</details>

<details>

<summary>My sensor appears to be connecting to the WiFi network, but no data has been transmitted. Why?</summary>

Check that the unit is running an **up-to-date firmware version**. [See here for details](wi-fi-connectivity/firmware-update-august-2023.md).

</details>

<details>

<summary>I can log into the app, but no sensor is listed <strong>and no data is shown</strong> - it prompts me to add a new sensor. Why?</summary>

This usually indicates that:

* You may have **created a second account** - in the app, go to **Settings > Account** and check which email you have signed in with.  If in doubt, log out, and try log in with a different email address!
* Or the sensor has been **deleted from the account** at some point - via the Settings > Sensor / Tank Settings screen. You can simply add the sensor again from the "Add New Sensor" screen.

</details>

<details>

<summary>My WiFi sensor is only sending data intermittently, and missing scheduled connections. What should I do?</summary>

On the main dashboard screen of the app - check the **received signal strength** (RSSI) of your TankMate unit (last known connection only). Common causes include:

* **Weak** **WiFi signal strength**
* **Obstructions** between the router and the tank (e.g. overgrown foilage)
* [See here for troubleshooting suggestions](wi-fi-connectivity/intermittent-data-issue-wifi.md)

</details>

<details>

<summary>How often should the TankMate sensor publish a reading?</summary>

By default, the sensor will send an updated level reading **every 12 hours** (2 per day). This can be **adjusted** in the mobile app under **Settings > Sensor / Tank Settings > Reading Frequency**. Having more readings per day will increase the accuracy of your daily water usage calculations, but will reduce battery life.

For the **R3W WiFi** sensor, a reading can be published to the server every 15 minutes (96 readings per day).

**If an alert is set**, the sensor will wake up to take a reading according to the reading interval set in the app (1 hour for WiFi sensors, adjustable for LTE). If the alert threshold is broken, the sensor will connect and send data.

For an **R3L** **Cellular / LTE** sensor, the maximum number of connections per day is 4. However, the sensor can be set to take a **reading every 15, 30 or 60 minutes** to check if an alert threshold has been broken. This allows users to gather more data, and receive timely alerts - without wasting power on frequent cellular connections.

</details>

<details>

<summary>How do I connect the TankMate to a second / new phone?</summary>

The TankMate unit **maintains a connection with your router / WiFi network** to be able to upload data to our servers - there is **no direct link to any mobile phone**.

Any phone or web browser can log in and see the same tank data, provided you are using the **same TankMate login details (email + password)**. You do not need to create a second account to monitor the sensor on a second phone.

* NOTE: using SIGN IN WITH APPLE will not support multiple phone logins

</details>

### General Questions

<details>

<summary>What batteries can be used with a TankMate sensor?</summary>

* 3 x AA Energizer Ultimate Lithium - **recommended\***&#x20;
* 3 x AA alkaline

**\*** **Battery life estimates in the app** are based on this type. If alkaline are used, the estimated battery life remaining will be less accurate, and the battery icon will appear half full.

</details>

<details>

<summary>Where can I find my device ID?</summary>

For new **R3W** and **R3L** sensors, the sensor will have a **QR code** attached to the base of the unit. Here you can find the device ID.&#x20;

Note: v2 sensors do not have a QR code. \
For existing sensors, you can also see the device ID in the TankMate app:

* The device ID can be found on the **home screen** of the app once logged in. To see the sensor details, click on the 'down arrow' icon to **expand the white box** on the home screen.&#x20;
* Alternatively, the device ID be found under **Settings > Sensor / Tank Settings**

</details>

<details>

<summary>How do I know which model I have?</summary>

Prior to 2022, only v1 and v2 WiFi models were sold - **v2 models use a submersible pressure sensor** with a cable. R3 models do not have an external cable - they use an internal radar sensor.

**TIP**: if you are not sure, you can check the **device ID**:

* v2 Sensors start with "esp-"
* R3W sensors start with "R3W"
* R3L sensors start with "R3L"

</details>

<details>

<summary>Does the sensor need much maintenance?</summary>

Very little, other than battery replacements.&#x20;

For **v1 / v2 sensors**, It is recommended to **clean the sensor probe annually**, by rinsing out any silt that has built up from the tank floor. The end cap be be unscrewed to make this easier. (Touching the **sensor diaphragm** inside the end cap should be **avoided**.)

</details>

<details>

<summary>Can the unit detect a leak?</summary>

**Yes**. **If the "Abnormal Usage Alert" has been enabled in the app** (Alerts tab) - the sensor will wake and take a reading **every hour**. If the level has dropped below the threshold set (under Alerts in the app), an abnormal usage alert will be sent as a **pop-up notification**.

Slow leaks are harder to detect. The best way to do this is to set the unit to update hourly (or every 15 minutes), and then compare the level readings after a sustained period of inactivity, e.g. 12 midnight through to 6am (or longer if possible).

</details>

<details>

<summary>How much variation should I expect to see between level readings?</summary>

Slight **variations** between level readings of **1-2mm** can be expected. While the sensor readings are extremely stable, a small variation in reading height can have a big effect on the volume calculations - in litres.

\
E.g. a **1mm** change in reading height on a 25,000L tank represents approximately **10L**. Which is only 0.04% of the tank volume! Therefore a 40L volume variation with a 2 x 25,000L tank setup would not be uncommon.

</details>
