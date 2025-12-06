# Location-tracker-sos-alert-device
IoT-based Location Tracking &amp; SOS Alert Device using ESP32, NEO-6M GPS, MPU6050 IMU, FSR sensors, SIM800L GSM, DHT22 &amp; MQ135. Real-time GPS tracking with posture detection via ConvLSTM AI. Panic button sends SOS SMS/location to emergency contacts. Vibration feedback, OLED display. Edge AI for fall alerts. Perfect for personal safety/wearables.​

# Materials List
- ESP32 DevKit V1 [memory:6]
- NEO-6M GPS Module [memory:15] 
- MPU6050 IMU [memory:10]
- 2x FSR Sensors
- SIM800L GSM Module
- DHT22 Sensor [memory:18]
- MQ135 Gas Sensor
- 0.96" OLED SSD1306
- Vibration Motor
- Push Button (SOS)
- 3.7V LiPo Battery
- Jumper Wires

# Connections

ESP32 → Components:

GPIO 4 → DHT22 Data

GPIO 5 → NEO-6M TX

GPIO 18 → NEO-6M RX

GPIO 21 → MPU6050 SDA

GPIO 22 → MPU6050 SCL

GPIO 19 → SIM800L TX

GPIO 23 → SIM800L RX

GPIO 2 → OLED SDA

GPIO 15 → OLED SCL

GPIO 13 → FSR1 (Seat)

GPIO 12 → FSR2 (Back)

GPIO 14 → SOS Button

GPIO 27 → Vibration Motor (+)

GND → All GND

3.3V → Sensors VCC

5V → SIM800L VCC

