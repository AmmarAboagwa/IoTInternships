# MQTT Broker

 The Mosquitto MQTT broker has been set up locally on a Raspberry pi. Sensor data will be sent over the broker to be stored in a database.

# Publisher

 The ESP8266 module publishes the sensor data to the broker which sends it to subscribers.

# InfluxDB

 The subscriber recieves the sensor data from the broker and stores it on influxDB which is set up locally.

# Grafana

 Stored data in influxDB is displayed on a Grafana dashboard setup locally.
