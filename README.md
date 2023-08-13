# STM32F4 MPU6050 USB-JST PCB

![PCB Preview](https://github.com/malto101/Basic_stm32_PCB/assets/70323154/79375607-8127-4bda-95ea-dc43b325059c)
![PCB Preview_1](https://github.com/malto101/Basic_stm32_PCB/assets/70323154/d85170a5-1563-4d5f-b150-83c8c056a0ae)


## Features

- **STM32F4 MCU:** The STM32F4 microcontroller provides a powerful and versatile platform for embedded applications. Its ARM Cortex-M4 core allows for efficient processing and control.

- **MPU6050 Sensor:** The MPU6050 combines a 3-axis accelerometer and a 3-axis gyroscope, enabling accurate motion tracking and tilt sensing.

- **USB Power:** The USB connector allows the board to be powered directly from a USB source, simplifying the power supply setup.

- **JST Connector:** The JST connector provides a convenient interface for debugging and programming the STM32F4 MCU.

- **SW Probing:** The integrated TC2030-NL connector facilitates Serial Wire debugging and probing, enabling efficient testing and development.

## Repository Contents

- **stm32tut.SchDoc/:** This File contains the Altium project files for the PCB layout, including the schematic and PCB layout design.

- **stm32BomDoc/:** The generated BOM files necessary for PCB manufacturing are located in this directory.

- **datasheets/:** Relevant datasheets for the STM32F4 MCU, MPU6050 sensor, and other components used on the board can be found here.

- **images/:** This directory contains images of the PCB layout, schematic, and other relevant visuals.

## Getting Started

1. **Clone the Repository:** Start by cloning this repository to your local machine:

2. **View Design Files:** Navigate to the `PCB1.PcbDoc/` directory to access the Altium project files. Open the schematic and PCB layout using KiCAD software.

3. **Manufacturing:** If you wish to manufacture the PCB, generate the Gerber files by using the directory. Upload these files to your preferred PCB manufacturer.

4. **Assembly:** Refer to the PCB layout and the component placement guides to assemble the components onto the PCB. Follow the datasheets for correct connections and soldering instructions.

5. **Testing:** Once the PCB is assembled, power it using the USB connector. Use the JST connector for debugging and programming the STM32F4 MCU. The TC2030-NL connector can be used for SW probing and testing.


