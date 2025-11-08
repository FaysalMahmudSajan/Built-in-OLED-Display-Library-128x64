# OLED-Display-Library 128x64

# Faysal_SSD1306 MicroPython Library

This library for microPython 128x64 oled Display.
To fulfill the python community group

## Usage:
1. Download `Faysal_SSD1306.py` from this repo.
2. Upload the file to your ESP32 using Thonny or ampy.
3. Import in your code:

```python
from Faysal_SSD1306 import Faysal_SSD1306
from machine import Pin, I2C

i2c = I2C(0, scl=Pin(22), sda=Pin(21))
oled = Faysal_SSD1306(128, 64, i2c)
```



Happy coding 
