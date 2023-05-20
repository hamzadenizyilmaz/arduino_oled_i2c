# Arduino Oled İ2C
In this code, we control the OLED display using the Adafruit_SSD1306 library. First you have to load the required library into the Arduino IDE. Then you can run your OLED display by uploading the code below to Arduino.

This code enables OLED display initialization, text printing and screen update. If your OLED display's I2C address is not 0x3C, you may need to edit the display.begin(SSD1306_SWITCHCAPVCC, 0x3C) line to reflect the correct address of your OLED display.

Note: This code uses the Adafruit_SSD1306 library. You can download this library from "Library Manager" using Arduino IDE.
