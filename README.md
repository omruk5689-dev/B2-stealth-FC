B2 FC

<img width="2160" height="1412" alt="3D_PCB1_2026-08-25" src="https://github.com/user-attachments/assets/1fd6679f-7273-41f2-a3d3-9520011c5827" />
<img width="2160" height="1434" alt="3D_PCB1_2026-08-25 (1)" src="https://github.com/user-attachments/assets/bace9824-b864-4a71-b59f-f9e67f017c51" />

A custom-designed flight controller built mainly for RC fixed-wing aircraft, while also being adaptable for drones and multirotors.

The idea behind this board was to create a capable and flexible flight controller from the ground up, using a powerful STM32F7-series MCU, a dedicated 6-axis IMU, and support for modern FPV systems such as DJI O4.

Features

- STM32F722RET6 flight-controller MCU
- ICM-20689 6-axis IMU
  - 3-axis gyroscope
  - 3-axis accelerometer
- Designed primarily for RC airplanes
- Can also be used for drones and multirotors
- Built-in DJI O4 unit connector
- FPV camera connectivity
- Multiple UART, SPI, I²C, GPIO, and other peripheral interfaces
- Dedicated power connections
- ESC and servo connectivity
- Receiver and telemetry support
- SWD programming and debugging interface

Main Controller

The heart of the board is the STM32F722RET6 which is an ARM Cortex-M7 based microcontroller giving sufficient performance for real-time applications.

F7 processor platform gives the board sufficient performance to support sensor processing, stabilization, communication, control algorithms, and other peripherals.

Motion Sensor

ICM-20689 based IMU is used in the flight controller.

It provides six-axis motion sensing using

- 3-axis gyroscope
- 3-axis accelerometer

This provides the flight controller the necessary motion sensing data for stabilization, orientation and flight-control calculations.

FPV and DJI O4 Compatibility

One of the key features of this board is its inbuilt DJI O4 system connector.

It is possible to directly connect a DJI O4 system and also use the board with regular FPV camera setup.

The idea is to provide enough flexibility to use different types of FPV configurations instead of tying the board to a single video system.

RC Aircraft Support

This board has been specifically designed for RC fixed-wing aircraft.

It has provisions for the components typically found in an RC aircraft, such as:

- Aileron, elevator and rudder servos
- ESC and throttle
- RC receiver
- FPV camera
- DJI O4 system
- Telemetry modules
- GPS and other peripherals

By configuring appropriate firmware, the board can be customized for different types of aircraft.

Drone Compatibility

Though the board has been primarily designed for fixed-wing aircraft, it is also possible to adapt the board for multirotors/drones.

The available performance and I/O capabilities make it possible to customize the board for different motor, ESC, receiver, sensor, GPS and telemetry configurations.

Firmware & Programming

While the hardware is designed to be flexible enough to not be bound to a particular flight-control software, it is possible to program and configure it using appropriate flight control firmware and software such as Betaflight, or any other suitable open source/custom flight control firmware.

This also makes it useful for experimenting with custom flight-control software and developing your own firmware.

Hardware Specification

Component| Specification
MCU| STM32F722RET6
IMU| ICM-20689
Motion Sensing| 3-axis accelerometer + 3-axis gyroscope
Primary Application| RC Fixed-Wing Aircraft
Secondary Application| Drones/Multirotors
FPV Support| Yes
DJI O4 Connector| Built-In
Receiver Interface| Supported
ESC/Servo Interfaces| Supported
Telemetry| Supported
Programming/Debugging| SWD
PCB Design Software| EasyEDA Pro

Design Approach

In designing this project, my prime objective was to build a flight controller from scratch rather than using an existing board commercially available.

I wanted to have a hardware that would be powerful enough for real world applications but at the same time flexible enough to experiment with different firmware, aircraft configurations and FPV systems.

This combination of STM32F722RET6, ICM-20689, flexible I/O capabilities and inbuilt DJI O4 connector makes the board robust enough for RC aircraft and future drone applications.

Credits

Designed and developed by Omer Ruknuddin

PCB Design: EasyEDA Pro
