# Rubber-Ducky-Bad-Ducky


## Quick Start Guide
Install and have your USB Rubber Ducky working in less than 5 minutes.

1. Download the latest release from the [Releases](abaychandrasurya/Rubber-Ducky-Bad-Ducky) page.

2. Plug the device into a USB port while holding the boot button. It will show up as a removable media device named RPI-RP2.

3. Install CircutlPython on the Pico .

Copy the adafruit-circuitpython-raspberry_pi_pico-en_US-9.2.1.uf2 file to the root of the Pico (RPI-RP2). The device will reboot and after a second or so, it will reconnect as CIRCUITPY.

4. Copy the lib folder to the root of the CIRCUITPY

5. Copy *.py to the root of the CIRCUITPY

6. Follow the instructions in README.md to enter setup mode

7. Copy your payload as payload.dd to the root of the CIRCUITPY

8. Unplug the device from the USB port and remove the setup jumper.

Enjoy your Pico-Ducky.

# Full Install Instructions

Install and have your USB Rubber Ducky working in less than 5 minutes.

1. Clone the repo to get a local copy of the files. `git clone https://github.com/abaychandrasurya/Rubber-Ducky-Bad-Ducky.git`

2. Download [CircuitPython for the Raspberry Pi Pico](https://circuitpython.org/board/raspberry_pi_pico/). *Updated to 9.2.1  

3. Plug the device into a USB port while holding the boot button. It will show up as a removable media device named `RPI-RP2`.

4. Copy the downloaded `.uf2` file to the root of the Pico (`RPI-RP2`). The device will reboot and after a second or so, it will reconnect as `CIRCUITPY`.

5. Download `adafruit-circuitpython-bundle-9.x-mpy-YYYYMMDD.zip` [here](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) and extract it outside the device.

6. Navigate to `lib` in the recently extracted folder and copy `adafruit_hid` to the `lib` folder on your Raspberry Pi Pico.

7. Find a script [here](https://payloadhub.com/blogs/payloads) or create your own one using Ducky Script and save it as `payload.dd` in the Pico.
