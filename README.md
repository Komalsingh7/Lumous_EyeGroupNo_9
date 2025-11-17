🌌 Lumous_Eye — Intelligent Smart Street-Lighting System

Energy-Efficient • AI-Enabled • Safety-Focused • Future-Ready

<p align="center"> <img src="https://img.shields.io/badge/Smart%20City-IoT-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Arduino-Powered-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Energy%20Saving-90%25+-brightgreen?style=for-the-badge"> <img src="https://img.shields.io/badge/Winner-Innovation%20&%20Tech%20Award-orange?style=for-the-badge"> </p>

🌟 Project Overview

Lumous_Eye is an intelligent street-lighting system that significantly reduces electricity usage while enhancing safety.
Using motion detection, environmental sensing, and automated brightness control, it ensures:

✔ Lights turn ON only when needed
✔ Dim-light safety mode during fog / rain / winter
✔ Maximum energy conservation for smart cities


Perfect for:
🛣️ Highways • 🏙️ Smart Cities • 🏘️ Residential Streets • 🅿️ Parking Lots • 🚶 Footpaths


✨ Key Features
🌙 Night-Only Mode (LDR Based)
LDR continuously checks ambient light
System activates only in darkness

🚶🚗 Smart Motion Lighting (PIR / IR Sensors)
Detects pedestrians or vehicles
Turns ON lights instantly
Auto OFF after inactivity

⏱️ 5-Second Intelligent Delay
Prevents abrupt darkness
No flickering on highways

🌫️ Fog / Rain / Winter Safety Mode (DHT11)
Triggers dim lighting when:
Temperature < 20°C, or
Humidity > threshold
Ensures visibility in harsh weather.

⚡ Extreme Energy Efficiency
OFF during daytime
ON only when motion + darkness
Dim mode only in risky climate
→ Saves up to 90% energy

🔗 System Architecture
🔹 Master Arduino
Handles LDR
Handles DHT11
Sends environment status to slave

🔹 Slave Arduino
Controls streetlights
Receives PIR / IR input
Manages timer + light intensity

🚀 Future Enhancements
✔ Adaptive brightness using IR distance
✔ Solar-powered version
✔ GSM / IoT cloud monitoring
✔ App dashboard (Android + Web)
✔ Emergency blinking mode for accidents
