# ESP32 Documentation - Introduction
---

**LESSON 1: INTRODUCTION**
---
### Table of Content
---
**1. Install of Arduino IDE**
**2. Setup the ESP32**
**3. Installation of ESP32 Driver**
&nbsp;
***NOTE:*** This documentation is for beginners on how they setup their ESP32 using Arduino IDE and aims to make them to easy setup and what they needs.
#### *1.1. INSTALL OF ARDUINO IDE*
---
- Go to https://www.arduino.cc/en/software

### *1.2 SETUP THE ESP32*
---
- **Step 1:** Go to Board Manager in Arduino IDE
- **Step 2:** Download ESP32 by Espressif
- **Step 3:** Go to File > Preference > Additional Board Manager URLs
- **Step 4:** In Additional Board Manager URLs paste this:
   &nbsp;
  
    **Install ESP32 Board**
    ```md
    https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
    ```
    and then paste also this in Additional Board Manager URLs
  
    **Software Packages**
    ```md
    https://dl.espressif.com/dl/package_esp32_index.json
    ```

### *1.3 Installation of ESP32 Driver*
---
if Select Board or ESP32 Port has not detected this is the solution.
- **Step 1:** find the need driver that saw in ESP32; on the right part of ESP32 name ***SILABS CP210 DCLOOX 2230+***
- **Step 2:** Go to this link https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads
- **Step 3:** Find the specific OS that you used.
- **Step 4:** When download is completed, go to zip file, and extract..
- **Step 5:** Find the ***silabser.inf***, then right-click then install.

***Note:***
Make sure that your ESP32 is connected.

# About
---
**Author:** Aron James L. Betinol
