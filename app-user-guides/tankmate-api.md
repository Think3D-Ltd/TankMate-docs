---
description: Using the TankMate API service
---

# TankMate API



{% hint style="success" %}
An API subscription costs $49 / year, per account. This subscription is managed and billed through the new TankMate web app / portal - due for release in July 2024.
{% endhint %}

{% hint style="info" %}
Note: API keys are free to trial for 30 days. Thereafter, an API subscription will be required.
{% endhint %}

### Accessing your API Key and User ID

To access your sensor data, a valid API Key is required, as well as your User ID (uid).  These can be accessed via the [TankMate web app](https://tankmateapp.co.nz/), under the Settings tab - see image below.

The Tankmate API includes two endpoints:

* **Sensor status**: which returns the current state of all sensors linked to one account. This includes the current tank level, fill percentage etc. as well as the hardware status - such as the battery health, signal strength etc.&#x20;
* **Level data**: returns all readings for a specific sensor (deviceID), for the previous X number of days

#### Access the [TankMate API Swagger UI documentation here](https://api.tankmate.app/docs)

<figure><img src="../.gitbook/assets/Screen Shot 2023-12-08 at 10.06.07 PM.png" alt=""><figcaption><p>"status" and "level-data" endpoints</p></figcaption></figure>



<figure><img src="../.gitbook/assets/Screen Shot 2023-12-08 at 10.30.45 PM.png" alt=""><figcaption><p>API Key accessed via the TankMate web app</p></figcaption></figure>
