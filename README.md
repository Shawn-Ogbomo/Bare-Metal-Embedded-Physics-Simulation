# STM32G474 2D Billiards Physics Simulation

This is an independent learning project focused on building a 2D billiards physics simulation executing directly on microcontroller hardware. The goal is to learn embedded programming and modern C++ initialization structures from scratch.

## 🛠️ The Hardware Stack (On My Desk)
* **Microcontroller Board:** NUCLEO-G474RE (ARM Cortex-M4 base board)
* **Display Expansion Shield:** X-NUCLEO-GFX01M2 (2.2" SPI LCD Screen)
* **Sensor Expansion Shield:** X-NUCLEO-IKS4A1 (MEMS Motion and Environmental Sensor Board)

## 📐 Learning Objectives & Constraints
* **Apply Ownership Semantics:** Using RAII and object lifetime lessons from Scott Meyers to manage hardware initializations safely.
* **Predictable Memory Footprints:** Forcing data into fixed-extent `std::array` configurations instead of dynamic vectors to guarantee the data doesn't exceed the chip's built-in RAM.
* **Understand the Hardware Lines:** Moving past desktop programming to learn how code communicates over physical serial connections (SPI for the screen, I2C for the sensors).

## 💻 Environment
* Development via Visual Studio Code (VS Code) utilizing CMake.
