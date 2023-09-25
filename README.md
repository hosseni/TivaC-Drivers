# Tiva C Drivers Readme

## Overview

This readme provides an overview of the Tiva C drivers, which are divided into two main categories: MCAL (Microcontroller Abstraction Layer) and HAL (Hardware Abstraction Layer). These drivers are designed to facilitate the development of applications for Tiva C series microcontrollers, providing an abstraction layer for various hardware peripherals.

### MCAL Drivers

MCAL drivers provide low-level access to the hardware peripherals on the Tiva C series microcontroller. These drivers abstract the hardware details, making it easier to interact with and configure the microcontroller's features. Below is a list of MCAL drivers available:

#### 00. GPIO (General-Purpose Input/Output)

- **Description**: The GPIO driver allows you to configure and control the digital input and output pins on the microcontroller. It provides functions for setting pin directions, reading input values, and writing output values.

#### 01. GPT (General-Purpose Timer)

- **Description**: The GPT driver enables you to configure and utilize the general-purpose timers on the microcontroller. These timers can be used for various timing and counting applications.

#### 02. SCB (System Control Block)

- **Description**: The SCB driver provides access to the System Control Block, which contains important system configuration and status registers. It allows you to configure system settings and obtain system information.

#### 03. SysTick

- **Description**: The SysTick driver is responsible for configuring and using the SysTick timer, which is a system timer used for generating periodic interrupts or timeouts.

#### 04. UART (Universal Asynchronous Receiver-Transmitter)

- **Description**: The UART driver enables communication via the UART interface. It allows you to configure and use UART for serial communication with other devices.

#### 05. ADC (Analog-to-Digital Converter)

- **Description**: The ADC driver facilitates analog-to-digital conversion. It allows you to configure and read analog input values from external sensors or devices.

### HAL Drivers

HAL drivers build upon the MCAL layer and provide a higher-level abstraction for specific hardware modules commonly used in embedded systems. These drivers simplify the development process by offering a more user-friendly API. Here is a list of HAL drivers available:

#### 00. LCD (Liquid Crystal Display)

- **Description**: The LCD driver abstracts the control of LCD modules, making it easier to display text and graphics on compatible LCD screens.

#### 01. ULTRASONIC

- **Description**: The ULTRASONIC driver simplifies interfacing with ultrasonic distance sensors commonly used in robotics and automation applications.

#### 02. SWITCH

- **Description**: The SWITCH driver abstracts the handling of push buttons and switches, making it easier to detect button presses and releases.

#### 03. MOTORS

- **Description**: The MOTORS driver provides a convenient way to control various types of motors, including DC motors and stepper motors, for robotic and motion control applications.

## Getting Started

To start using these drivers in your Tiva C microcontroller project, follow these general steps:

1. Include the necessary driver files in your project.

2. Initialize the appropriate driver(s) for the peripherals you intend to use.

3. Use the driver functions to configure and control the hardware peripherals as needed.

4. Refer to the documentation and example code for each driver for specific usage instructions.

## Documentation

Detailed documentation for each driver can be found in their respective source code files. Additionally, you may find example projects and usage guidelines in the documentation folder or repository where the drivers are hosted.
