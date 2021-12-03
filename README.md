# Awesome Zephyr-RTOS

Refer to [Awesome-zephyr](https://github.com/fkromer/awesome-zephyr) for a comprehensive list. 

This list is focused on collecting examples of the **use** of Zephyr. It helps me understand the RTOS better, if I can look through various examples. 

> ❗❗❗ Please send pull requests, and help improve the list.


# Reference Projects
## Applications
- [A small self balancing Robot](https://github.com/skalldri/project-wobble) : Contains custom drivers, documentation
- [FOC Motor Control Firmware](https://github.com/teslabs/spinner), also refer to the corresponding [talk](https://www.youtube.com/watch?v=9XKQqPuZh9w&t=1s)
- [Pinetime smartwatch using Nordic nrf52 and zephyr RTOS](https://github.com/najnesnaj/pinetime-zephyr) : Contains custom drivers, documentation
- [RISC-V Electronic Badge open source software Zephyr RTOS application](https://github.com/antmicro/riscv-badge-application) 
- [MG100 Zephyr RTOS based firmware](https://github.com/LairdCP/MG100_firmware)
- [A set of utility and driver classes to support IC peripherals in Zephyr RTOS.](https://github.com/theheraldproject/zephyr-devices) : Contains example for board description
- [Example BLE application using Zephyr RTOS](https://github.com/DonBraulio/zephyr_ble_example)
- [PWM controlled by bluetooth through the Zephyr RTOS using the nrf52dk board](https://github.com/Johan-Garrido/minimal_BT_PWM)
- [Board template for building Zephyr RTOS for SiFive Freedom E-Series products](https://github.com/sifive/zephyr-sifive-freedom-template)
- [A Zephyr RTOS based Lorawan node](https://github.com/fcgdam/zLorawan_Node)
- [Desay D6 smart watch zephyr rtos](https://github.com/najnesnaj/dsd6-zephyr)
- [Getting Started with Zephyr RTOS](https://github.com/bdcabreran/zephyr_RTOS_nucleo_l476rg) ⭐
- [PWM controller servo motors](https://github.com/octobotics/motor_control)

## Drivers
- [BlackBerry trackpad Zephyr RTOS driver](https://github.com/protobits/bbtrackpad_zephyr)
- [HCSR04](https://github.com/smeetsomaiya/zephyr-sensor-driver-plus-app/tree/master/drivers/sensor/hcsr04)


# Libraries
## Internal APIs
### Essentials
- [C standard library and ERRNO (❗)](https://docs.zephyrproject.org/latest/reference/libc/index.html)
- [Kernel Service](https://docs.zephyrproject.org/latest/reference/kernel/index.html): Threads, Synchronization, Scheduling, etc.
- [File System](https://docs.zephyrproject.org/latest/reference/file_system/index.html)
- [Displays](https://docs.zephyrproject.org/latest/reference/display/index.html)
- [Peripherals](https://docs.zephyrproject.org/latest/reference/peripherals/index.html): GPIO, I2C, PWM, etc.

### Great to have
- [Formatted Printing](https://docs.zephyrproject.org/latest/reference/misc/formatted_output.html): printf-like
- [Logging](https://docs.zephyrproject.org/latest/reference/logging/index.html)
- [Shell](https://docs.zephyrproject.org/latest/reference/shell/index.html)
- [Settings](https://docs.zephyrproject.org/latest/reference/settings/index.html)
- [utilities](https://docs.zephyrproject.org/latest/reference/util/index.html)
- [State Machine Framework](https://docs.zephyrproject.org/latest/guides/smf/index.html): Allows for hierarchical state machines

### More useful APIs
- [Some data structures](https://docs.zephyrproject.org/latest/reference/data_structures/index.html)
- [Checksum, JSON, JWT](https://docs.zephyrproject.org/latest/reference/misc/index.html)
- [Timing for optimization and measurements](https://docs.zephyrproject.org/latest/reference/timing_functions/index.html)
- [Task Watchdog](https://docs.zephyrproject.org/latest/reference/task_wdt/index.html)
- [Emulators for I2C, SPI and EEPROM](https://docs.zephyrproject.org/latest/guides/emulator/index.html#available-emulators)

## External
- [Arduino package based on ZephyrRTOS (or Arduino API module for Zephyr RTOS)](https://github.com/soburi/arduino-on-zephyr)
- [Calendar API for Zephyr RTOS](https://github.com/bpbradley/zcalendar)

---

# Getting Started
## Tutorials
- [Zephyr Tutorial for Beginners](https://github.com/maksimdrachov/zephyr-rtos-tutorial)
- [zephyr RTOS examples](https://github.com/ChunghanYi/zephyr-examples)
- [Repository for custom Zephyr RTOS based boards](https://github.com/LairdCP/zephyr_boards)

## Templates
...

# Platformio
- [Zephyr documentation](https://docs.zephyrproject.org/latest/guides/platformio/index.html)
- [Platformio documentation](https://docs.platformio.org/en/latest/frameworks/zephyr.html?utm_source=docs.zephyrproject.org)

## Examples
- Blinking LED on [Nxp iMx-RT](https://github.com/platformio/platform-nxpimxrt/tree/develop/examples/zephyr-blink) and [Arduino Due](https://github.com/platformio/platform-atmelsam/tree/master/examples/zephyr-blink)
- [Using the logger subsystem](https://github.com/platformio/platform-atmelsam/tree/master/examples/zephyr-subsys-logger)
- [Interfacing with an LCD without the use of the Driver API model](https://github.com/platformio/platform-atmelsam/tree/master/examples/zephyr-drivers-lcd-hd44780)
- [Multithreading and Synchronization](https://github.com/platformio/platform-nxpimxrt/tree/develop/examples/zephyr-synchronization)
- [Using the CAN bus](https://github.com/platformio/platform-ststm32/tree/develop/examples/zephyr-drivers-can)
- [Writing thin C++ abstrastions](https://github.com/platformio/platform-ststm32/blob/develop/examples/zephyr-cpp-synchronization/src/main.cpp)
- [HID mouse over USB](https://github.com/platformio/platform-ststm32/tree/develop/examples/zephyr-subsys-usb-hid-mouse)

# Tools
- [Header include map generator for Zephyr RTOS](https://github.com/smrtos/ZephyrIncludeMap)
