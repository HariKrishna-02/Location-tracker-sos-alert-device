# Location-tracker-sos-alert-device
IoT-based Location Tracking &amp; SOS Alert Device using ESP32, NEO-6M GPS, MPU6050 IMU, FSR sensors, SIM800L GSM, DHT22 &amp; MQ135. Real-time GPS tracking with posture detection via ConvLSTM AI. Panic button sends SOS SMS/location to emergency contacts. Vibration feedback, OLED display. Edge AI for fall alerts. Perfect for personal safety/wearables.​

# Materials List
- ESP32 DevKit V1 [memory:6]
- NEO-6M GPS Module [memory:15] 
- SIM800L GSM Module
- LCD Display
- Buck Converter
- Buzzer
- Push Button (SOS)
- 3.7V LiPo Battery
- Jumper Wires

# Connections

ESP32 Pin Connections:

GPIO4  → GPS TX (NEO-6M)

GPIO18 → GPS RX (NEO-6M)

GPIO16 → SIM800L TX

GPIO17 → SIM800L RX

GPIO21 → I2C LCD SDA

GPIO22 → I2C LCD SCL

GPIO2  → Buzzer (+)

GPIO0  → SOS Button

5V     → Buck Converter IN

3.3V   → GPS/LCD VCC

GND    → All GND

SIM800L VCC → Buck Converter OUT (4.0-4.2V)

[memory:15][memory:6]
