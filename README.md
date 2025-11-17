🌌 Lumous_Eye — Intelligent Smart Street-Lighting System
Energy-Efficient • AI-Enabled • Safety-Focused • Future-Ready
<p align="center"> <img src="https://img.shields.io/badge/Smart%20City-IoT-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Arduino-Powered-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Energy%20Saving-90%25+-brightgreen?style=for-the-badge"> <img src="https://img.shields.io/badge/Winner-Innovation%20&%20Tech%20Award-orange?style=for-the-badge"> </p>
🌟 Project Overview

Lumous_Eye is an advanced intelligent street-lighting system designed to dramatically reduce electricity consumption while enhancing public safety.

Using smart motion detection, environment sensing, and automatic brightness control, the system ensures that lights turn ON only when necessary, and remain in a low-intensity safe mode during darkness, fog, rain, or cold weather.

Perfect for:
🛣️ Highways • 🏙️ Smart Cities • 🏘️ Residential Streets • 🅿️ Parking Lots • 🚶 Footpaths

✨ Key Features
🌙 Night-Only Mode — LDR Based

Lights activate only when LDR detects low ambient light.

🚶🚗 Smart Motion Lighting — PIR / IR Sensors

Streetlights turn ON only when a pedestrian or vehicle is detected.

⏱️ 5-Second Intelligent Delay

Lights remain ON for 5 seconds after motion disappears — avoids sudden darkness.

🌫️ Fog / Rain / Cold Weather Safety Mode

Using DHT11:

Temperature < 20°C

OR Humidity > Threshold

➡ Automatically triggers safe-mode dim lighting for increased visibility.

⚡ Extreme Energy Efficiency

Lights remain OFF during daytime and activate only when needed.
Designed for large-scale energy conservation.

🔧 Simple & Affordable

Low-cost components, easy wiring, high reliability.

🧠 System Working Diagram
        ┌─────────────┐
        │    LDR      │
        └──────┬──────┘
               │ Night?
          Yes  ▼   No
         ┌─────────────┐
         │  Motion?     │ ← PIR / IR Sensors
         └─────┬───────┘
               │Yes
               ▼
      ┌───────────────────┐
      │ Light ON (5 sec)  │ ← Timer Module
      └───────────────────┘

   ┌──────────────────────────────────┐
   │   Temperature < 20°C OR High Humidity? │ ← DHT11
   └──────────────────────────────────┘
               │Yes
               ▼
        Safe-Mode Dim Light

🧩 Hardware Requirements
Component	Quantity	Purpose
Arduino Uno	2	Core control units
PIR / IR Sensors	3	Detect motion (per streetlight)
LDR + 10k Ω Resistor	1	Day/Night detection
DHT11 Sensor	1	Temperature & Humidity sensing
LEDs / Street Lamps	4	Light output
Breadboard + Jumpers	—	Wiring
5V Power Supply	—	Microcontroller power
Common Ground	—	System stability
🔗 System Architecture
Uses Two Arduino Units:

Master Arduino
Handles LDR + DHT11 (environment detection)

Slave Arduino
Controls lights based on PIR / IR signals

Communication via:
🔘 Digital pins (recommended)
🔘 Or Serial (optional)

🛠️ How the System Works
1️⃣ LDR — Day/Night Detection

Bright → Light OFF

Dark → Activate sensing system

2️⃣ PIR / IR Sensor — Motion Detection

Human/vehicle detected → Signal HIGH

Triggers timed lighting

3️⃣ Timer Module — 5s Lighting Delay

Even if motion stops → light stays ON for 5s

Prevents flickering on highways

4️⃣ Climate-Based Safety Mode

If Temperature < 20°C
OR Humidity is high (fog, rain, winter)
➡ Lights stay dimly ON for safety

📸 Images / Demo

(Add your project images, wiring diagrams, Proteus, breadboard design)

![System Overview](your_image_path)
![Breadboard Wiring](your_image_path)
![Proteus Simulation](your_image_path)

🛠️ Future Enhancements

✔ Automatic brightness scaling using IR distance data
✔ Solar-powered implementation
✔ GSM/IoT cloud data logging
✔ App dashboard for monitoring energy savings
✔ Emergency blinking mode for accidents

🚀 Why Lumous_Eye Stands Out

Real-time adaptive lighting

High energy savings (up to 90%)

Climate-aware safety

Supports long highway deployments

Uses low-cost hardware

High reliability + modular design


