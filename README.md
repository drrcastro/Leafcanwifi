# Leafcanwifi
Connecting a Nissan leaf to a wifi network to check soc

ze0 and aze0 are untested, all versions available. Older cars could be connected next to the driver footwell.

It will connect to your wifi after you insert the desired ip, ssdi and pass... or create a network for you to connect.

![Screenshot](https://raw.githubusercontent.com/CrAzYDr1veR/Leafcanwifi/main/screenshot.png)

Based on the idea of this page using esphome:
https://blog.jingo.uk/notes-on-integrating-a-nissan-leaf-ze1-and-home-assistant/



You need the following hardware:

esp32-c3 (cheaper)

SN65HVD230 VP230 CAN Board Network Transceiver

dc-dc converter

24pin gateway extention cable or just jam the wires in like i did LOL



gateway pinout:

https://nissanleaf.carhackingwiki.com/index.php/CAN_Gateway

With the help of ai this was built without the need of home assistant so you can check soc while charging and without the need to go to the car and press the key on.
Homeassistant integration should work anyway.

And it works, power consumption is 50ma +-, feel free to make it better as i am not a programmer.
