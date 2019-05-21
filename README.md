# Arduino-OTA-and-Painless-Mesh
This shows how to use Arduino OTA and Painless Mesh together in PlatformIO

# Set-up
First copy Main.cpp and platform.io into your project. Add your Station SSID (Router name) and Station Password (Wifi password)
into Main.cpp.

Upload to device.

Your device will then connect to your Router and its IP will be shown in the serial terminal. Copy that address (CTRL+SHIFT+C)
and put into PlatformIO inside upload_port.

**RESTART YOUR DEVICE**

Then press upload to upload OTA. PlatfomIO will make the update OTA with the upload_port line uncommented out. 
