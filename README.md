# Tasks1
           To install the ESP32 board in your Arduino IDE:
1.	 install the arduino ide 1.8.5 or updater version .
2.	In  Arduino IDE, go to File> Preferences.
3.	Enter the following into the “Additional Board Manager URLs” field: "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json". and then press OK
4.	Open the Boards Manager. Go to Tools > Board > Boards Manager.
5.	Search for ESP32 and press install button for the “ESP32 by Espressif Systems“: that’s it. It should be installed after a few seconds.
                          -here will start Testing the Installation -
6.	Plug the ESP32 board to your computer. With your Arduino IDE open, follow these steps
7.	Select your Board in Tools > Board menu (in my case it’s the DOIT ESP32 DEVKIT V1)
8.	Select the Port (if you don’t see the COM Port in your Arduino IDE, you need to install the CP210x USB to UART Bridge VCP Drivers):
9.	Open the following example under File > Examples > WiFi (ESP32) > WiFiScan.
10.	 A new sketch opens in your Arduino IDE.
11.	Press Upload button in the Arduino IDE.and  Wait a few seconds while the code compiles and uploads to your board.
12.	If everything went as expected, will appear message “Done uploading.” 


