# MoodFox – STM32 Light-Reactive OLED Display 🦊💡

**A simple and engaging embedded project using an STM32F100C8 microcontroller, an LDR, and a 0.96" SSD1306 OLED.
The OLED displays different fox images depending on ambient light intensity:**

- Bright environment → Happy fox
- Dark environment → Scared fox

All source code, images, and project files are included in this repository.

---

### Features

- Reads ambient light using the STM32 internal ADC
- Displays custom images on an SSD1306 OLED via I2C
- Light-based image switching (happy/scared fox)
- Custom images stored as C-arrays
- Uses a clean pre-written SSD1306 driver
- Beginner-friendly and fully documented

---

### Hardware Requirements

- STM32F100C8 (or STM32F103 compatible)
- SSD1306 OLED display (I2C)
- LDR + 10k resistor (voltage divider)
- Breadboard and jumper wires

---

### How It Works

- The LDR and 10k resistor create a voltage divider.
- The ADC reads this voltage to determine light intensity.
- A simple threshold decides whether it is “light” or “dark.”
- Depending on the light level, the OLED displays either:
  - happy fox
  - scared fox
- Images are converted to monochrome C-arrays using online tools.

---

### Getting Started

1. Open the project in STM32CubeIDE (or any STM32 toolchain).
2. Build and flash the firmware to your board.
3. Change the light around the LDR and observe the OLED reaction.



