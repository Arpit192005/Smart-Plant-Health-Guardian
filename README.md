# Smart-Plant-Health-Guardian
A simple ESP32-based plant monitoring and automatic watering system designed as a STEM learning project for Grades 9–10.

The system measures soil moisture, temperature, and humidity every 2 seconds. The ESP32 analyzes the readings and displays them on a 0.96" OLED. If the soil is too dry and environmental conditions indicate that watering is needed, the system activates a water pump through a relay.

🔧 Features
Soil moisture monitoring
Temperature & humidity monitoring
Automatic watering
OLED real-time display
Red LED → Water needed
Green LED → Plant condition OK
ESP32-based control
🛠️ Components

ESP32 • Capacitive Soil Moisture Sensor • DHT22 • 0.96" OLED • Relay Module • 5V Water Pump • LEDs

⚙️ Working

Sensors → ESP32 → Decision → OLED + LEDs → Pump

The project demonstrates how electronics and basic automation can be applied to precision agriculture and plant care.
