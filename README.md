# 📏 Arduino Distance Calibrator with LED Alerts & LCD Display

## 🔧 Components Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- I2C LCD Display (16x2)
- 2x Green LEDs (for short distance)
- 2x Yellow LEDs (for medium distance)
- 1x Red LED (for long distance)
- 5x 220Ω resistors
- Breadboard
- Jumper wires

## 📘 Project Description
This project measures the distance to an object using an ultrasonic sensor and displays the result on an LCD. Based on the measured distance, it activates different LEDs as visual indicators:

- **< 10 cm** → Green LEDs ON  
- **10–20 cm** → Yellow LEDs ON  
- **> 20 cm** → Red LED ON  

This is a great beginner-friendly project to learn sensor interfacing, display handling, and conditional LED control with Arduino.

## 📁 Files Included
- `distance_calibrator.ino` – Main Arduino sketch
- `circuit.png` – Wiring diagram
- `README.md` – Project documentation

## ✅ How to Use
1. Connect all components as per the circuit diagram.
2. Open `distance_calibrator.ino` in Arduino IDE.
3. Select the correct board (Arduino Uno) and COM port.
4. Upload the code to your Arduino board.
5. Power the Arduino and observe:
   - LCD displaying real-time distance
   - LEDs lighting up based on how close/far your hand or object is

## ⚠️ Notes
- Make sure the LCD I2C address is correct (`0x27` or `0x3F`)
- Always use resistors for LEDs to prevent damage
- Keep ultrasonic sensor unobstructed and pointed straight

## 👨‍💻 Author
- Your Name (you can link your GitHub profile)

## 🪄 License
This project is open-source and free to use under the [MIT License](LICENSE).
