# STM32_UART_PWM_Command

This project demonstrates how to control an LED using UART string commands on an STM32 NUCLEO-F446RE board.

The user can send commands from a serial terminal such as PuTTY, Tera Term, or VS Code Serial Monitor to control PWM brightness, enable breathing LED mode, and read ADC values.

## Hardware

- Board: STM32 NUCLEO-F446RE
- LED: PA5 / TIM2_CH1
- UART: USART2
  - PA2: TX
  - PA3: RX
- ADC: PA0 / ADC1_IN0
- Baud rate: 115200


## Features

- UART string command receiving
- PWM LED brightness control
- Breathing LED mode
- ADC value reading
- Serial command interface

## How to Run
-Open the .ioc file with STM32CubeIDE.
-Generate code if needed.
-Build the project.
-Flash to the STM32 NUCLEO-F446RE.
-Open a serial terminal at 115200 baud.
-Type help and press Enter.

## Demo
<img width="1083" height="381" alt="螢幕擷取畫面 2026-05-14 134050" src="https://github.com/user-attachments/assets/8b74a292-f2c4-40b9-a875-f9ad15f0caf7" />
<img width="3024" height="4032" alt="IMG_8177" src="https://github.com/user-attachments/assets/509dfd64-7a52-449d-8cb8-7bbaa2b9e9e8" />
