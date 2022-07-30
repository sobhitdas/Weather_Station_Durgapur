# Weather_Station_Durgapur

It explains how to log Humidity & Temperature data on the cloud. We can use Thingspeak as a cloud service provider and DHT11 to measure temperature and humidity

# Pin diagram:

![Screenshot (159)](https://user-images.githubusercontent.com/59681238/181936887-84ef34f6-d34e-4c23-8063-1f620a49a933.png)

# Data as seen on Thingspeak Cloud:

![Screenshot (160)](https://user-images.githubusercontent.com/59681238/181936923-a9c0827f-6528-4ce9-822c-1ac00c3b4b90.png)

# About DHT11

The DHT11 is a basic, ultra low-cost digital temperature and humidity sensor. It uses a capacitive humidity sensor and a thermistor to measure the surrounding air and spits out a digital signal on the data pin (no analog input pins needed).

It’s fairly simple to use but requires careful timing to grab data. The only real downside of this sensor is you can only get new data from it once every 2 seconds, so when using the library, sensor readings can be up to 2 seconds old.

# Youtube tutorial:

How2electronics

# Thingspeak public server link:

https://thingspeak.com/channels/1816586

1816586 being the channel ID

