# Zephyr template project for zephyr v3.7.0

## Overview
This project serves as a Zephyr template to be used as a model for other projects. It provides a structured foundation with all necessary configuration and setup files, allowing me/you to quickly start mine/your Zephyr-based application.

## Building and Runn/home/aleks/toolkits/zephyrproject/zephyr


## Boards


### Esp32 
Updates esp32 binary dependencies
```sh
west update
west blobs fetch hal_espressif
```

#### Compiling and Flashing

```sh
west build -b esp32_devkitc_wroom/esp32/procpu -pauto
```

#### Monitoring
```sh
picocom -b 115200 /dev/ttyUSB?
```


