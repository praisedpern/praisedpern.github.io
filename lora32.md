# [LilyGO](http://lilygo.cn/) TTGO Boards and Devices

 [ebay/praisedpern](https://www.ebay.co.uk/usr/praisedpern/) - [github/praisedpern](https://www.github.com/praisedpern/)

## TTGO Lora32

### Pin Diagram

[![Lora32 Pinout](lora32-pinout-small.jpg)](lora32-pinout.jpg)

### Setting up Arduino IDE

1. Download and install the Arduino IDE from [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software), or from your system's package manager.

2. Open Arduino and select Tools > Manage Libraries...

3. From Library Manager, search for LoRa by Sandeep Mistry and click Install.

3. Close Library Manager and select Tools > Board: > Boards Manager...

4. From Boards Manager, search for esp32 and click Install.

5. Once it is installed, close Boards Manager then select Tools > Board: > ESP32
   Arduino > TTGO Lora32-OLED V1.

6. Plug the board into your PC with a USB cable and wait for any drivers to install. Go to Tools > Port: and select the COM port for your Lora32. If Arduino IDE can't find the port for your board, you may need to download and install the UART driver from [https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers).
