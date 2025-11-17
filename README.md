# Lumous_Eye
# 🚀 Project Overview
 Luminous Eye is an  intelligent street-lighting system  designed to achieve large-scale energy savings using smart sensing and automation. The system automatically switches street lights ON only when vehicle movement or human motion is detected, significantly reducing unnecessary power consumption. Additionally, for public safety, a low-intensity lighting mode remains active during darkness, foggy conditions, or when the temperature drops below 24°C. By combining motion detection, environmental sensing, and automated control, Luminous Eye provides an efficient, safe, and eco-friendly lighting solution for modern smart cities.

 # This project uses:
 # PIR Sensor – detects pedestrians/vehicles

Parts List

2 × Arduino Uno
3 × IR proximity sensors (or PIR if preferred) — one per street light
1 × LDR (with 10k resistor voltage divider)
1 × DHT11 temperature/humidity sensor
4 × Street lamps (or lamp simulators / LEDs for prototyping)
Wires, breadboard, power supplies (5V for Arduinos)
Common ground between Arduinos and sensors
The system saves energy by activating lights only when needed.

✨ Features
🌙 Night-only operation using LDR
🚗 Light turns ON when motion is detected
⏱️ Stays ON for 5 seconds after motion disappears
⚡ Energy efficient
🔧 Simple, low-cost, reliable hardware
🛣️ Perfect for highways, smart cities, parking lots, and footpaths

🧠 How the System Works
1️⃣ LDR Day/Night Detection
Day: LDR resistance ↓ → Light OFF
Night: LDR resistance ↑ → System activated
2️⃣ PIR Motion Detection
When PIR detects movement → sends HIGH signal to 555 Timer
3️⃣  Timer – 5 Second Delay
Timer triggers ON when PIR gets HIGH
Light stays ON for 5 seconds even after PIR returns LOW
Prevents sudden darkness on highways
4️⃣ Low Temperature / Fog / Rain / High Humidity Safety Mode
System monitors DHT11 temperature & humidity
If Temperature < 20°C, OR Humidity is high (fog/rain) → Safety Light turns ON
Provides necessary lighting even with no motion detection
Improves visibility during winter, foggy nights, rain, or low-visibility situations
Uses low-power dim mode to save energy.

![Uploading ChatGPT Image Nov 17, 2025, 09_50_37 PM.png…]()
