# ESP32-Serial-Bridge

Transparent WiFi (TCP, UDP) to all three UART Bridge, supports both AP and STATION WiFi modes. The .ino file is the code for the ESP32. Use Arduino IDE for ESP32 to compile and upload it to the ESP32.
I made this project in order to connect Flight equipment devices devices like (Radio, Vario FLARM), to a Flight Computer (Kobo, Smartphones etc.),  but it is not limited to that. You can use it wherever you want, but on your own risk. Read license file for more details.
Accesspoint IPAdress: 192.168.4.1
AP SSID: LK8000
AP Password: Flightcomputer
Used Ports:
192.168.4.1:8880  <-> COM0
192.168.4.1:8881  <-> COM1
192.168.4.1:8882  <-> COM2

===============================================================

Used Libraries: (must be install in the arduino IDE):

https://github.com/espressif/arduino-esp32

===============================================================

example usecases:

https://www.youtube.com/watch?v=K2Hia06IMtk

https://www.youtube.com/watch?v=GoSxlQvuAhg

# Hardware
I recomend to start your project with a Node32s or compatible Evalution board. For a TTL to RS232 Level conversion search google for "TTL RS3232 Converter"

Pinning 
COM0 Rx   GPIO03 
COM0 Tx   GPIO01 
COM1 Rx   GPIO02 
COM1 Tx   GPIO04 
COM2 Rx   GPIO16
COM2 Tx   GPIO17 

https://tech.scargill.net/wp-content/uploads/2017/05/ESP326.jpg

A discussion incl. the similar ESP8266 projekt can be found here:

http://www.postfrontal.com/forum/topic.asp?TOPIC_ID=8467
