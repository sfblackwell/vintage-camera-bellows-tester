# Bellows Tester

## Simons @pimoroni Tiny2040 / BH1745 Based Vintage Camera Bellows Light Tighness Tester

This is a small device for testing the light tighness of vintage cameras.

Vintage cameras often use cloth bellows and light seals. These wear over time and can start to allow light through which can spoil the film in the camera

This is the first prototype of a device thta can be placed inside the camera to detect any light leakage. 

The device is about an 30mm * 30mm * 15 mm. The aim is to have a second version that is about 20mm * 25 * 10mm.

To operate, the device is switched on it is place inside the camera the rear cover is closed. After a delay the device will make a series of light readings over a few minutes and will store them in a file call results.txt. This file can then be viewed on a computer.

At the end of the test run the Leds on the Tiny2040 are also set to RED for light detected (Fail) or Green for light not detected (Pass). These LED'scan be viwed thru the back of the case.

### *** This is a work in progress ***

### *** I am not a coder or programer, so please excuse the chaos ***

### Items Used:
- Processor   [Tiny2040 RP2040 development board](https://shop.pimoroni.com/products/tiny-2040?variant=39560012234835)
- I2C Sensor  [BH1745 Luminance and Colour Sensor Breakout](https://shop.pimoroni.com/products/bh1745-luminance-and-colour-sensor-breakout)
- Battery     [Adafruit 20mm Coin Cell Breakout w/On-Off](https://shop.pimoroni.com/products/adafruit-20mm-coin-cell-breakout-w-on-off-switch-cr2032?variant=821160901)
- Micropython [pimoroni-tiny2040-v1.19.16-micropython](https://github.com/pimoroni/pimoroni-pico/releases/download/v1.19.17/pimoroni-tiny2040-v1.19.17-micropython.uf2)
- Case        [Adapted 3d Printed Case ](https://www.printables.com/model/166430-case-for-adafruit-qt-py-rp2040-and-seeed-xiao-rp20)

![trilobot plus controller half](https://user-images.githubusercontent.com/122044826/212179922-8c774104-d420-4df5-91af-77403d0690f8.jpg)


