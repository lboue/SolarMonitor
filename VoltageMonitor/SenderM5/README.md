## Solar Energy System M5Dial sender

- [Watch Monitor Your Solar Energy System Remotely Using ESP32 (Easy DIY)](https://youtu.be/qzITUL2FK7k?si=jzOzGdcNWpmXHgjK) on YouTube
- [M5Dial doc](https://docs.m5stack.com/en/core/M5Dial)

## Setup

### Arduino libraries

- [M5-ADS1115](https://github.com/m5stack/M5-ADS1115)
- [M5Dial](https://github.com/m5stack/M5Dial)
- [M5GFX](https://github.com/m5stack/M5GFX)
- [M5Unified](https://github.com/m5stack/M5Unified)
- [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI)

### Board parameters

M5Dial/M5StampS3 comes with 8MB of built-in Flash:
- Flash size: 8MB
- Partition scheme: 8MB with spiffs

![image](https://github.com/user-attachments/assets/2e2eed98-4d13-4651-ac36-cc2ed2ea120b)

### Voltage module

Connect the to PORT A（RED）:
  - SDA: GPIO13
  - SCL: GPIO15
