---
description: Using the TankMate API service
---

# TankMate API

{% hint style="success" %}
A TankMate Premium Web Subscription is required to use the API service - AUD 49 / year, per account. This subscription is managed and billed through the new TankMate web app / portal.
{% endhint %}

### Accessing your API Key and User ID

To access your sensor data, a valid API Key is required, as well as your User ID (uid).  These can be accessed via the [TankMate web portal](https://tankmate.app/), under the Account tab.

The Tankmate API includes two endpoints:

* **Sensor status**: which returns the current state of all sensors linked to one account. This includes the current tank level, fill percentage etc. as well as the hardware status - such as the battery health, signal strength etc.&#x20;
* **Level data**: returns all readings for a specific sensor (deviceID), for the previous X number of days

#### Access the [TankMate API Swagger UI documentation here](https://api.tankmate.app/docs)

<figure><img src="../.gitbook/assets/Screen Shot 2023-12-08 at 10.06.07 PM.png" alt=""><figcaption><p>"status" and "level-data" endpoints</p></figcaption></figure>

