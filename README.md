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
