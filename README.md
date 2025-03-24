## Project 1: Sound Controlled RGB LED Matrix Using Raspberry Pi Pico

### Description

This project demonstrates an innovative way to control an RGB LED matrix using sound. By interfacing a sound sensor and an RGB LED strip with a Raspberry Pi Pico, the LED matrix lights up automatically in response to ambient sound vibrations, such as music or noise. Utilizing the Raspberry Pi Pico’s Programmable I/O (PIO), this DIY project creates a mesmerizing LED display that blinks in patterns synchronized with sound, making it a perfect ambient lighting solution for music visualization.

### Overview

This project uses the Programmable I/O (PIO) hardware on the Raspberry Pi Pico to control a WS2812B RGB LED matrix, which reacts to ambient sound detected by a connected sound sensor. The setup features a 128×64 pixel display made up of digital flexi strips of RGB LEDs, housed in a custom enclosure. The RGB LEDs are energy-efficient, with low driving voltage, high brightness, a wide scattering angle, excellent consistency, low power consumption, and a long lifespan. Using C/C++ and the Raspberry Pi Pico SDK, the system monitors a music source to display frequency levels and incorporates simple beat detection, creating a captivating visualization of music.

### Components Used

- **Raspberry Pi Pico**: The microcontroller that controls the LED matrix.
- **Grove Sound Sensor**: Detects ambient sound to trigger the LED matrix.
- **WS2812B RGB LED Strip**: Creates the vibrant 128×64 pixel display.
- **Lead-Free Solder Wire**: Used for assembling the circuit.

### Setup Instructions

1. **Hardware Setup**:
   - Connect the WS2812B RGB LED strip to the Raspberry Pi Pico using the appropriate GPIO pins (refer to the pinout diagram in the project documentation).
   - Attach the Grove Sound Sensor to the Raspberry Pi Pico via the analog input pin.
   - Solder the connections securely using lead-free solder wire.
   - House the LED matrix in a custom enclosure for a clean setup.

2. **Software Setup**:
   - Install the Raspberry Pi Pico SDK and set up your development environment (e.g., Visual Studio Code with the Pico C/C++ extension).
   
