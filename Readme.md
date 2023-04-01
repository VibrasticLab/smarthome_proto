# SmartHome Module

This repository contains development files for smarthome monitoring prototyping,
which intended for student final project.

Currently doesnt support any control mechanism, only measuring.

## Multi Module Version 1

### Sensors Options
- Temperature/Humidity Sensors (I2C)
    + HTU21D: [Tokped](https://www.tokopedia.com/akhishop/htu21d-temperature-and-humidity-sensor-module)
    + SHT20: [Tokped](https://www.tokopedia.com/akhishop/sht20-digital-temperature-and-humidity-sensor-module-i2c-communication)
    + SHT31-D: [Tokped](https://www.tokopedia.com/akhishop/sht31-d-temperature-humidity-sensor-module)
    + GY-213V: [Tokped](https://www.tokopedia.com/cncstorebandung/gy-213v-hdc1080-high-precision-temperature-and-humidity-sensor-module)
- Light Intensity Sensors (I2C)
    + GY302/BH1750: [Tokped](https://www.tokopedia.com/akhishop/gy-302-light-intensity-bh1750-module-sensor-intensitas-cahaya)
- CO2 Air (Analog)
    + MG-811: [Tokped](https://www.tokopedia.com/khursiot/dfrobot-analog-co2-gas-sensor-for-arduino-mg-811-sensor)
- MEMS Microphone (I2S)
    + INMP441: [Tokped](https://www.tokopedia.com/aifrobotic/inmp441-omnidirectional-microphone-module-mems-i2s-interface)

### Display Options
- LCD Alphanumeric (I2C)
    + 16x02: [Tokped](https://www.tokopedia.com/akhishop/lcd-16x2-blue-backlight-with-i2c-module)

### ESP32 Pinout

| I/O | Func | Connect |
|:---:|:----:|:-------:|
| EN | RESET | Pull-up Button |
| 0 | FLASH | Pull-up Button |
| 1 | TX | UART0 |
| 2 | IND | LED |
| 3 | RX | UART0 |
| 13 | SPI WS | MIC |
| 14 | SPI SCK | MIC |
| 15 | BOOT-LOG | Pull-done Resistor |
| 21 | SDA | I2C Line |
| 22 | SCL | I2C Line |
| 23 | SPI DATA | MIC |
| 34 | ADC | CO2 |




