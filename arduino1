Step 1: Configuring Arduino IDE (Windows)

1. Download the files through the link: https://github.com/espressif/arduino-esp32

2. Unzip the file and copy the contents to the following path:

C: / Users / [YOUR_USER_NAME] / Documents / Arduino / hardware / espressif / esp32
Note: If there is no directory "espressif" and "esp32", just create them normally.

3. Open the directory

C: / Users / [YOUR_USER_NAME] / Documents / Arduino / hardware / espressif / esp32 / tools
Run the file "get.exe".

4. After the "get.exe" finishes, plug the ESP32, wait for the drivers to be installed (or install manually).
Ready, now just pick the ESP32 board in "tools >> board" and compile your code.

Step 2: WiFi Scan
Here's an example of how to look for available WiFi networks near the ESP-32, as well as 
the signal strength of each of them. With each scan, we will also find out which network has the best signal strength.

Step 3: Code
First let's include the library "WiFi.h", it will be necessary to allow us to work with the network card of our device.

#include "WiFi.h"
Here are two variables that will be used to store the network's SSID (name) and signal strength.

String networkSSID = "";
int strengthSignal = -9999;

Step 4: Setup
In the setup () function, we will define the WiFi behavior mode of our device. In this case, 
since the goal is to search for available networks, we will configure our device to work as a "station".

Step 5: Loop
In the loop () function, we will search for the available networks and then print the log in
the found networks. For each of these networks we will make the comparison 
to find the one with the highest signal strength.

