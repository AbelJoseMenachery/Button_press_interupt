# STM32 Button Interrupt Project

This project demonstrates external interrupt handling using the STM32 Nucleo-H723ZG development board.

## Board Used
- STM32 Nucleo-H723ZG

## Features
- GPIO external interrupt
- Button press detection
- LED control using interrupt callback
- STM32 HAL drivers

## Tools Used
- STM32CubeIDE
- STM32 HAL Library
- Git & GitHub

## Project Structure

Core/
Drivers/
Debug/
STM32CubeIDE/
Button_press_interupt.ioc


## How It Works
- A button press triggers an external interrupt.
- The interrupt callback executes.
- LED state changes based on interrupt event.

## Build and Flash
1. Open project in STM32CubeIDE
2. Build project
3. Connect Nucleo board
4. Flash using ST-LINK

## Author
Abel Jose Menachery
