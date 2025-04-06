# 🔥 Fire Fighting Robotic Vehicle

The Fire Fighting Robotic Vehicle is a smart, autonomous robot designed to detect and extinguish fires in hazardous environments. The robot uses flame sensors to detect fire, a water pump to extinguish it, and is capable of navigating obstacles, either autonomously or via remote control.

## 🚀 Project Highlights

- Detects fire using flame sensors
- Extinguishes fire using a water pump system
- Controlled manually or autonomously
- Built using Arduino 
- Can be deployed in indoor environments for safety missions

---

## 📦 Features

- 🔥 Fire detection using flame sensor
- 💧 Water spraying mechanism
- 🧭 Obstacle avoidance (using IR or Ultrasonic sensors)
- 📡 Wireless control (Bluetooth / RF / Wi-Fi)
- 🔋 Battery-powered and portable
- 🌐 IoT integration for remote monitoring (optional)

---

## ⚙️ Hardware Components

- Arduino UNO 
- Flame Sensors
- Water Pump + Relay Module
- Motor Driver (L298N)
- DC Motors + Wheels
- Chassis Frame
- IR / Ultrasonic Sensors (for obstacle detection)
- Power Supply (Battery Pack)
- Bluetooth Module (HC-05) / Wi-Fi for remote control

---

## 🧠 Software & Libraries

- Arduino IDE
- Servo.h, NewPing.h, etc. (depending on your sensors)
- MIT App Inventor / Blynk (for mobile control, optional)
- Real-time data via Firebase or Thingspeak (optional IoT version)

---

## 🛠️ How to Run

1. **Assemble the robot:**
   - Connect all sensors, motors, and water pump to the microcontroller.
   - Mount them securely on the chassis.

2. **Upload the code:**
   - Use Arduino IDE to upload the appropriate code to Arduino/NodeMCU.

3. **Power the robot:**
   - Use a battery pack (typically 12V for motors + 5V for controller/sensors).

4. **Test the system:**
   - Place a flame source (like a lighter or candle) in front of the robot.
   - The robot should move toward the flame, stop at a safe distance, and activate the water pump.

---
## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---
