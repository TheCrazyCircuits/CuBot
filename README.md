# CuBot 🤖

**CuBot** is an interactive ESP32-powered desktop companion designed to bring personality and life to your workspace.  
It combines expressive OLED animations, motion sensing, touch interaction, weather updates, and intelligent sleep behavior into a compact open-source robotic companion.

Built using the ESP32 platform, CuBot focuses on smooth animations, responsive interactions, and a futuristic minimalist aesthetic.

---

# ✨ Features

- 🎭 Animated expressive OLED face
- 👀 Smooth idle eye movement
- 😴 Sleep mode with floating "Zzz" animation
- 🫳 Petting interaction using touch sensor
- 📳 Motion & shake detection using MPU6050
- 🌦️ Real-time weather display using OpenWeather API
- 🕒 Clock mode with NTP time synchronization
- ⚡ Cinematic boot animation sequence
- 📶 WiFi-enabled ESP32 system
- 🧠 Modular and expandable architecture

---

# Images 📸

![CuBot Hero](assets/images/hero.jpg)

---

## ✨ Face Mode
![Face Mode](https://github.com/TheCrazyCircuits/CuBot/blob/5cd57695c5a19d078a40788411685de32b3bcbde/WhatsApp%20Image%202026-05-26%20at%2012.24.24%20PM.jpeg)

## 🌦 Weather Mode
![Weather](assets/images/weather.jpg)

## 😴 Sleep Mode
![Sleep](https://github.com/TheCrazyCircuits/CuBot/blob/43dc16e847ca98da79a8165a3579857eb3281de4/WhatsApp%20Image%202026-05-26%20at%2012.24.25%20PM.jpeg)

## 🔧 Setup
![Setup](assets/images/setup.jpg)

---

# 🛠 Hardware Used

| Component | Description |
|---|---|
| ESP32 | Main microcontroller |
| SH1106 OLED Display | 128x64 I2C OLED display |
| MPU6050 | Accelerometer + gyroscope |
| Capacitive Touch Sensor | User interaction input |

---

# 🔌 Wiring Connections

## OLED Display (SH1106G)

| OLED Pin | ESP32 Pin |
|---|---|
| SDA | GPIO 21 |
| SCL | GPIO 22 |
| VCC | 3.3V |
| GND | GND |

I2C Address: `0x3C`

---

## MPU6050

| MPU6050 Pin | ESP32 Pin |
|---|---|
| SDA | GPIO 21 |
| SCL | GPIO 22 |
| VCC | 3.3V |
| GND | GND |

---

## Touch Sensor

| Touch Sensor Pin | ESP32 Pin |
|---|---|
| Signal | GPIO 4 |
| VCC | 3.3V |
| GND | GND |

---

# 🧠 System Behavior

## Boot Sequence
- Random glitch flickers
- Circular iris expansion
- Scanline reveal animation
- Final pulse inversion effect

---

## Face Mode
- Smooth figure-eight eye movement
- Random blinking animations
- Touch interaction with happy face response
- Motion-triggered vibration animation

---

## Sleep & Clock Mode
- Auto sleep after inactivity
- Floating "Zzz" animation
- Clock display after extended idle time
- Real-time synced time and date

---

## Weather Mode
- Triple-tap activation
- Real-time weather data
- Temperature
- Feels-like temperature
- Humidity
- Weather conditions

---

# 📡 Connectivity

CuBot uses:
- WiFi via ESP32
- NTP for time synchronization
- OpenWeather API for weather data

---

# 🚀 Installation

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/CuBot.git
```

---

## 2. Install Required Libraries

Install these libraries from the Arduino Library Manager:

- Adafruit GFX
- Adafruit SH110X
- Adafruit MPU6050
- Adafruit Unified Sensor
- WiFi
- HTTPClient
- ArduinoJson
- NTPClient

---

## 3. Configure WiFi & API

Create a file named:

```cpp
config.h
```

Example:

```cpp
#define WIFI_SSID "YOUR_WIFI_NAME"
#define WIFI_PASSWORD "YOUR_WIFI_PASSWORD"

#define WEATHER_API_KEY "YOUR_OPENWEATHER_API_KEY"
#define CITY_NAME "YOUR_CITY"
```

---

## 4. Upload Code

- Select ESP32 board
- Select correct COM port
- Upload firmware

---

# 🌦 OpenWeather Setup

1. Create an account at:
https://openweathermap.org/

2. Generate an API key

3. Add the key inside `config.h`

---

# 📸 Media

> Add photos, GIFs, and demo videos here.

Example:
- Boot animation GIF
- Face interaction demo
- Weather mode showcase
- Sleep mode showcase

---

# 🧩 Future Plans

- 🔊 Sound effects
- 🎙 Voice interaction
- 📱 Mobile app integration
- 🧠 AI assistant integration
- 🔋 Battery-powered version
- 🖨 Custom 3D printed shell
- 🌈 RGB ambient lighting
- ☁ OTA firmware updates

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve CuBot:
- Fork the repository
- Create a new branch
- Commit your changes
- Submit a pull request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Creator

Created by Shubhankar.

CuBot was built as a passion project focused on blending embedded systems, expressive interaction, and futuristic desk companion design.

---

# ⭐ Support

If you like this project:
- Star the repository
- Share it with makers and developers
- Build your own CuBot

Because every desk deserves a little personality. 🤖
