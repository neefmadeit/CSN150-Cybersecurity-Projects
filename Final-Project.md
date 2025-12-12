# Cybersecurity : CSN150

## Name of Project
Final Project

## Purpose
My final project.

## Tools used 
- Wazuh
- Linux
- Promox

## Links to documentation

##### Links: https://documentation.wazuh.com/current/installation-guide/wazuh-server/index.html


## Steps I followed
1. Connect the ESP32-CAM to computer
2. Open the Arduino IDE Software
3. In your Arduino IDE, go to File > Examples > ESP32 > Camera > CameraWebServer
4. Modify the code to act as an access point
5. Select camera model in board_config.h
6. Define an SSID name and a password to access the ESP32-CAM
7. Remove code from line 109 - 118
8. After that add WiFi.setSleep(false);
9. Add WiFi.softAP(ssid, password);
10. Upload the code to the ESP32-CAM
11. Connect to the access point
12. Open your web browser and type the IP address 192.168.4.1
13. View the video stream
   
## Problems / Solutions
Don't forget to select the camera model in board_config.h #define CAMERA_MODEL_AI_THINKER // Has PSRAM
## Final Report
In this project I learned how to set the ESP32-CAM as an access point. When the ESP32-CAM is set as an access point, devices with Wi Fi capabilities can connect directly to the ESP32-CAM without the need to connect to a router. I can also view a video stream of the ESP32-CAM sees.
