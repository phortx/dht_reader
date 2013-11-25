# dht_reader
dht_reader.c is a small tool written in c, which reads a DHT-22 or 11 temperature sensor over the GPIO of the Raspberry Pi. That's my bugfixed version of [bzyx implementation](https://github.com/bzyx/pi-dht22).

Contains a executable, which is compiled for ARM.


## Usage
  ./dht_reader sensor pin

Where "sensor" is either 22 or 11 depending on your sensor (DHT-22 or DHT-11) and "pin" is the gpio pin to which you connected the sensor data pin.
