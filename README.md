# ttn-gps-tracker
This is the first commit of an Arduino Sketch for an GPS-Tracker to work with The Things Network.
This Sketch uses TinyGPS, the Arduino LMIC-Library by Matthijs Kooijmanand and the hartware serial of an Adafruit Feater LoRa.
I use sample Code from Pieter Hensen https://github.com/Teumaat/ttn-tracker

The folder contais the payload decoder for TTN.

The folder node-red contains a sample flow adding a geohash and storing data in InfluxDB.
