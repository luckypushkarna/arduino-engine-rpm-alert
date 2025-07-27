# arduino-engine-rpm-alert
# RPM LED Indicator using Arduino

This project simulates a basic RPM alert system using Arduino, LEDs, and a potentiometer. LEDs light up based on RPM value and provide a visual warning system. This is useful for understanding real-world engine behavior and is inspired by automotive embedded systems.

## 🔧 Components Used
- Arduino UNO
- Potentiometer (10k)
- 6x LEDs (Red, Blue, Green, White, Yellow)
- 220Ω resistors
- Buzzer
- Breadboard & Jumper wires

## 🧠 Working Principle
The potentiometer simulates RPM input. Based on the analog value, different LEDs light up at certain thresholds. At high RPM, a buzzer triggers along with blinking LEDs.

## 💻 Code
The Arduino code reads analog input and maps it to simulated RPM values. LEDs are controlled based on set ranges.

## 📁 Folder Info
- `code/` contains the Arduino `.ino` file

