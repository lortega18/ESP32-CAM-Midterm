# ESP32-CAM-Midterm

# Cybersecurity 150 Midterm
ESP32 WiFi Spy Camera

# Purpose
Using an ESP32 camera module to set up a Wi-Fi spy camera.

# Equipment

ESP32Cam
USB-C Data Cable

Link to Documentation Followed
Youtube Video 1:https://www.youtube.com/watch?v=tx09GFGgVwA
Other Link: https://randomnerdtutorials.com/esp32-cam-video-streaming-web-server-camera-home-assistant/

# Steps I followed
1. Installing ESP32 Board on Arduino
2. Select AI THINKER ESP32-CAM
3. Choose PORT COMM5
4.Camera WebServer and input my SSID and PW
5. Compile Sketch
6. Connect cam and select Upload
7. At first it completed no issues. But unable to view the Ip address camera came up with
   
8.  Attempted to redue upload now receiving an error message "Sketch uses 1510669 bytes (48%) of program storage space. Maximum is 3145728 bytes.
Global variables use 70388 bytes (21%) of dynamic memory, leaving 257292 bytes for local variables. Maximum is 327680 bytes.
esptool.py v4.5.1
Serial port COM5
Connecting......................................

A fatal error occurred: Failed to connect to ESP32: No serial data received.
For troubleshooting steps visit: https://docs.espressif.com/projects/esptool/en/latest/troubleshooting.html
Failed uploading: uploading error: exit status 2"

9. Attempted all steps again, upload fine, still unable to find IP address to view camera.
10. Attempted to install some drivers to see if that was the issue
11. Unable to view camera
12. Reset computer and redid all steps one more time.
13. After uploading and going into Serial Monitor, I finally have an IP ADDRESS!!
14. Searched Ip address on browser, and it took me to the Toggle OV2640 Settings
15. Set the Resolution to lowest quality to start it off, left other settings as in, turned on Face detection, and there we have it! A working camera.

Problems
Im not sure what the issue was. Everything in Arduino IDE was done correctly following all steps. I installed, uninstalled, re-installed all steps and I some how could not view what the ip address was. Only thing I could come up with is maybe I have a firewall I didnt know I had or maybe since the camera does not have an sd card. 
After carefully looking through all steps, finally got the camera working
