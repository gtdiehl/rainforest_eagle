<h1>Rainforest Eagle</h1>
<h2>Description</h2>
Rainforest Eagle-200 Component for Home Assistant
Creates the following components:
<li> Sensor - Power Demand of the Electric Meter (kWatts)</li>
<li> Sensor - Total Energy delivered through the Electric Meter (kWh)</li>
<li> Sensor - Total Energy received from the Electric Meter (kWh)</li>

<h2>Example</h2>
<pre>
sensor:
  - platform: rainforest_eagle
    ip_address: ip_address
    cloud_id: CLOUD_ID
    install_code: INSTALL_CODE
</pre>
