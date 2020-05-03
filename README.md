# RainbowCandyHAT(reload)
[原作者的README](./README-origin.md)

由于原作者已经很久不更新，所以fork来更新此仓库

# 源码文件结构
```
RainbowCandyBoard/
|-- buzzer/
|   |-- buzzer_bcm2835/
|   |-- buzzer_fs/
|   |-- buzzer_python/
|   |-- buzzer_shell/
|   |-- buzzer_wiringPi/
|
|-- ds18b20
|   |-- python/
|   |-- README.md
|   |-- sysfs/
|
|-- fan
|   |-- fan_wiringPi/
|   |-- README.md
|
|-- ir
|   |-- README.md
|
|-- key
|   |-- key_bcm2835/
|   |-- key_python/
|   |-- key_wiringPi/
|
|-- led
|   |-- led_BoardRev1.0/
|   |-- led_BoardRev2.0/
|
|-- oled
|   |-- bcm2835/
|   |-- python/
|   |-- readme
|   |-- wiringPi/
|
|-- rgb
|   |-- README.md
|   |-- rgb
|   |-- rgb.c
|
|-- schematic
|   |-- RainbowCandyBoard_Rev1.0.pdf
|   |-- RainbowCandyBoard_Rev2.0.pdf
|
|-- uart
|   |-- RaspberryPi2/
|   |-- RaspberryPi3/
|   |-- Readme.md
|
|-- .gitattributes
|-- .gitignore
|-- LICENSE
|-- README-origin
|-- README.md
```
### 目前支持：
| 外设    | wiringPi           | Python              | BCM2835 C          | sysfs             | Kernel |
| ------- | ----------------- | --------------------| ------------------ | -------------------| ------ |
| LED灯   | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:    |
| 蜂鸣器  | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:    |
| 按键    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:    |
| RGB灯   | :white_check_mark: | :x:                | :x:                | :x:                | :x:    |
| 温控风扇 | :white_check_mark: | :x:                | :x:                | :x:                | :x:    |
| ds18b20 | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: | :x:    |
| OLED    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                | :x:    |
