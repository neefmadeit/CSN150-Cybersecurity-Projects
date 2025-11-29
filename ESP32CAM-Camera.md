# Cybersecurity : CSN150

## Name of Project
ESP32-CAM Camera

## Purpose
Use the ESP32-CAM's Camera

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Tools used 
- Arduino

## Links to documentation

##### Links: https://lastminuteengineers.com/getting-started-with-esp32-cam/


## Steps I followed
1. Connect the ESP32-CAM to computer
2. Open the Arduino IDE Software
3. In your Arduino IDE, go to File > Examples > ESP32 > Camera > CameraWebServer
4. Select the camera model in board_config.h
6. Define an SSID name and a password to my home's router
7. Upload the code to the ESP32-CAM
8. Opended up a serial monitor window and got the ESP32-CAM's ip address
9. Open a web browser and type the IP address 192.168.0.109
10. Viewed the video stream
11. Took a screenshot
   
## Problems / Solutions
I did not encounter any problems with this porject.
## Final Report
In this project I learned how to setup the ESP32-CAM with a webserver that shows a videostream from the camera and I took a picture with it.
