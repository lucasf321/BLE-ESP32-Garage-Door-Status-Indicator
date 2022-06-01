# BLE-ESP32-Garage-Door-Status-Indicator-Arduino-IDE
2 client ESP32's monitor and communicate (via write) the status of 2 garage doors to a server ESP32 which illuminates the corresponding LED when a door is open.
This code is written for the ESP32 in Arduino IDE.
This code uses the BLE libraries that exist in the standard ESP32 distribution in Arduino. No separate library download is necessary. 
These BLE libraries were developed by an individual named Neil Kolban (not Expressif). His Github location is located here: https://github.com/nkolban
The 2 client files and 1 server file use the "BLE_client" and "BLE_server" examples for the ESP32 as templates. Only minor changes were made to map the server LED pins and input pins for the clients.
