# FPGA Projects

## Description
This is where I'll be displaying all my project / things I'm doing in order to build a better foundation with FPGA's! If you would like to use any of this code or have suggestions feel free to reach out! These ideas were generated with the help of ChatGPT as I have no idea where to start! NONE OF THIS CODE IS WRITTEN BY IT, that ruins the point of learning and gaining wrinkles! This will also be done in conjunction with my other project of building my own CPU from the ground up, if you want to check it out click [here](https://github.com/Azureum/MPU) or go to my repos!

## Tools
The current FPGA I am using is the Nexys Video Artix-7 FPGA, which has the Xilinx Artix®-7 XC7A200T and a bunch of other features! You can purchase it here: [here](https://digilent.com/shop/nexys-video-artix-7-fpga-trainer-board-for-multimedia-applications/).

I also have a Seven Segment Display PMOD from Digilent, where you can find here: [here](https://digilent.com/shop/pmod-ssd-seven-segment-display/).

## 🔌 Basic Hardware Interfacing

- [ ] Read Input from Switches & Display on LEDs
    - Implement logic to read switch states and output values to LEDs.
- [ ] Button Debounce Circuit
    - Design a debounce circuit to stabilize button inputs for reliable detection.
- [ ] 7-Segment Display Control
    - Write a program to control a 7-segment LED display, including binary-to-decimal conversion for display output. 
    - Utilize the PMOD 7-segment display.
- [ ] LED Blinking with Clock Divider
    - Use a clock divider to make an LED blink at a controlled rate.
- [ ] PWM Controller for LED Brightness
    - Implement a Pulse Width Modulation (PWM) controller to adjust LED brightness.

---

## 🎛 Advanced Peripheral Interfacing

- [ ] UART Communication
    - Implement UART for serial communication to send and receive data over a simple interface.
- [ ] SPI Communication
    - Send and receive data over SPI (Serial Peripheral Interface) for high-speed peripherals, especially for SD card interfacing.
- [ ] I2C Sensor Interface
    - Interface with an I2C sensor (e.g., temperature sensor) for real-time data acquisition.
- [ ] SD Card Interface via SPI
    - Implement SPI communication to read and write data to an SD card, logging data or handling file operations using the FatFs file system.
- [ ] PWM Audio Output
    - Use PWM to generate audio signals and output sound through a speaker.

---

## ⏱ Timing & Clocking

- [ ] Clock Frequency Generation
    - Use the FPGA’s onboard clock to generate multiple clock frequencies for various applications.
- [ ] Clock Divider
    - Implement a clock divider to create slower clock signals for time-dependent tasks.
- [ ] Real-Time Clock (RTC) Counter
    - Design a real-time clock (RTC) counter to keep track of time continuously, outputting the time on the PMOD 7-segment display.
- [ ] Timer with Interrupts
    - Implement a timer module capable of generating interrupts based on time conditions.

---

## 📟 Memory & Storage

- [ ] Block RAM (BRAM) Usage
    - Store data in Block RAM (BRAM) and implement simple read/write operations.
- [ ] Simple RAM Module
    - Build a simple RAM module to read and write data in your FPGA design.
- [ ] DDR2 SDRAM
    - Use DDR2 SDRAM for larger data storage (requires MIG controller for interfacing).
- [ ] Flash Memory Interface
    - Implement read and write operations for Flash memory.

---

## 🧠 Basic CPU Enhancements

- [ ] Stack Operations
    - Implement a basic stack with push/pop functionality for storing return addresses or temporary data.
- [ ] Interrupt Handling
    - Design interrupt handling to respond to asynchronous events (e.g., button presses).
- [ ] Bootloader
    - Create a simple bootloader to load programs into RAM for execution.
- [ ] Random Number Generator (LFSR)
    - Implement a hardware-based random number generator using a Linear Feedback Shift Register (LFSR).

---

## Fun Projects & Expansions

- [ ] Hardware Stopwatch
    - Design a simple hardware stopwatch using a 7-segment display for real-time timing.
    - Use an external switch to start/stop the timer.
- [ ] Reaction Timer Game
    - Build a reaction timer game that uses switches for input and LEDs for output.
    - Test reaction times and display the score on the PMOD 7-segment display.
- [ ] ALU Calculator
    - Design a basic Arithmetic Logic Unit (ALU) calculator using switches for input and 7-segment displays for output.
- [ ] VGA Graphics Controller
    - Implement a VGA graphics controller for displaying images or graphics on a monitor.
- [ ] Morse Code Generator
    - Create a Morse code generator that outputs patterns through an LED based on button inputs.
- [ ] Hardware Music Player
    - Design a hardware music player that plays preloaded tunes using PWM audio output, and control the tunes through switches.
- [ ] SD Card Data Logger
    - Create a system where the FPGA logs data to an SD card using SPI.
    - Use the SD card to store timestamps or sensor data. Retrieve the data later via UART or display it on the PMOD 7-segment display.
- [ ] SD Card File Reading and Writing
    - Build a project that reads and writes files to an SD card.
    - Log events or timestamps, and display the status of file operations on the 7-segment display.
- [ ] AI Accelerator
    - Implement a simple Neural Network (NN) accelerator on the FPGA for tasks like image classification or basic pattern recognition.
    - Use preprocessed data to classify inputs (e.g., image data processed via a VGA interface).
    - Implement a lightweight feedforward neural network or multi-layer perceptron (MLP), optimizing operations for parallel processing in hardware.
    **Features:**
    - Leverage FPGA’s parallelism for matrix multiplications.
    - Input data from an external sensor or VGA display.
    - Display the classification result on the 7-segment display or via UART.
- [ ] Cryptographic Accelerator (AES Encryption)
    - Implement an AES (Advanced Encryption Standard) hardware accelerator to perform encryption and decryption of data.
    - Design the accelerator to take plaintext from switches or the SD card, encrypt it, and then store or display the encrypted data.
