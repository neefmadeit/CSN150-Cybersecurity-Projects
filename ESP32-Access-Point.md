# Cybersecurity : CSN150

## Name of Project
ESP32 Access Point

## Purpose
Create an ESP32 Wifi Access Point. 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Links: https: https://randomnerdtutorials.com/esp32-cam-access-point-ap-web-server/


## Steps I followed
1. Connect the ESP32 Cam to computer
2. Open the Arduino IDE Software
3. In your Arduino IDE, go to File > Examples > ESP32 > Camera > CameraWebServer
4. Modify the code to act as an access point
5. Select camera model in board_config.h
6. Define an SSID name and a password to access the ESP32-CAM
7. Remove code from line 109 - 118
8. After that add WiFi.setSleep(false);
9. Add WiFi.softAP(ssid, password);
10. Upload the code to the ESP32
11. Connected to the access point
12. 
   
## Problems
Don't forget to select the camera model in board_config.h #define CAMERA_MODEL_AI_THINKER // Has PSRAM
## Final Report
