## **Please note this has been merged in to Home Assistant v0.97 and will be updated in that [repository](https://github.com/home-assistant/home-assistant/tree/dev/homeassistant/components/rainforest_eagle) only from now on.**

<h1>Rainforest Eagle</h1>
<h2>Description</h2>
Rainforest Eagle-200 Component for Home Assistant
<p>Creates the following components:
<li> Sensor - Power Demand of the Electric Meter (kWatts)</li>
<li> Sensor - Total Energy delivered through the Electric Meter (kWh)</li>
<li> Sensor - Total Energy received from the Electric Meter (kWh)</li>

<h2>Example</h2>
<pre>
sensor:
  - platform: rainforest_eagle
    ip_address: 1.1.1.2
    cloud_id: 123456
    install_code: 4234343242343242
</pre>
