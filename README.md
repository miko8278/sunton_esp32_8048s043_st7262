# sunton_esp32_8048s043_st7262
This is a vibecoded example for the Sunton-ESP32-8048S043 with the ST7262 driver and
the G911-Touchpanel Driver.
It's broken, the screen keeps moving from left to right, might be fixable though.
If you want a fully working setup, check out
- [PlatformIO setup] https://github.com/miko8278/CYD-Sunton-ESP32-8048S043-ST7262

# Setup
This setup uses esp-idf and LVGL.

- [esp-idf] https://github.com/espressif/esp-idf
Install it and don't forget using . ./export.sh

Afterwards go into this repo and do
`idf.py build flash monitor`

If something doesn't build try
`idf.py fullclean`

You can stop the idf monitor with `ctrl+]`
