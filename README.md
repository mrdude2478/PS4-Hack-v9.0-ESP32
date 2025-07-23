# Web Flash PS4-Hack-v9.0-ESP32 - Lolin S2 Mini or ESP32-S2 with 4MB flash and PSRAM
https://mrdude2478.github.io/esp32s2/

# Web Flash PS4-Hack-v9.0-ESP32 - Lolin S3 Pro/ESP32-S3-WROOM-1 N16R8 Boards
https://mrdude2478.github.io/esp32s3/
<br/>
<br/>
LED Settings for Lolin S3 Pro
Set Onboard LED to WS212B
GPIO 38
Colour Order 2
<br/>

Other S3 boards:
ESP32-S3-WROOM-1 N16R8 Boards, typical WS2182B led is mapped to GPIO pin 48 or 47, use colour order 1

# Guide, flash from online flasher

Once flashed, unplug your dongle and plug it back in again, the blue onboard led will come on.

Connect to computer to wifi SSID "ESP32"

Once connected go to: http://192.168.0.1

Move your mouse over "File Manager", then select "Configure Settings"

Check Use Wifi checkbox and enter the SSID and WIFI password your home WiFi uses.

Click Save & Reboot.

Connect to you home wifi

In your web browser go to: http://esp32.local

Select: "Tar Installer" from the dropdown menu.
Click "Download & Unpack" button (if download fails,click on "Download to PC", then install via the offline tar installer).

The dongle will reboot - once the blue light comes back on you can go back to the settings page and disable Wifi and then connect your ps4 to the ESP32 wifi network.

# Screenshots (need updated)
![Main Page](https://i.imgur.com/5kyxgYW.png)

![Updates Page](https://i.imgur.com/yNW28WB.png)

![Information Page](https://i.imgur.com/HC3yaVW.png)

![File Manager Page](https://i.imgur.com/xTstYTj.png)

![File Editor Page](https://i.imgur.com/tScZEj3.png)

![Configuration Page](https://i.imgur.com/4nJlz4D.png)

![TAR Installer Page](https://i.imgur.com/2oINUNS.jpeg)

![Dropdown](https://i.imgur.com/bpzatvr.png)
