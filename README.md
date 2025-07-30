# Ultrasonic Sensor Project 🦇📏

This **Ultrasonic Sensor** project uses echolocation—like a bat—to measure distance, detect motion, and trigger responses. Using an ultrasonic sensor, it emits sound waves and listens for echoes to determine how far away an object is. Depending on distance, it can light up an RGB LED, play a sound with a piezo buzzer, or respond to a push button input. It's a great way to explore how sensors interact with output components in real time.

---

## 📦 Components

- Arduino Uno (or compatible)
- Breadboard
- Ultrasonic Distance Sensor (HC-SR04 or similar)
- RGB LED
- Resistors (for RGB LED and other components)
- Piezo buzzer
- Push button
- Jumper wires
- USB cable (for power and programming)

---

## 🔧 Installation & Setup

1. **Build the circuit:**
   - Connect the **ultrasonic sensor**:
     - VCC → 5V  
     - GND → GND  
     - Trig → Digital Pin (e.g., 9)  
     - Echo → Digital Pin (e.g., 10)
   - Wire the **RGB LED** with current-limiting resistors to PWM pins (e.g., 3, 5, 6).
   - Connect the **piezo buzzer** to a digital pin (e.g., 8) with GND.
   - Attach the **push button** with a pull-down resistor to a digital input pin (e.g., 2).
   - Use the breadboard to lay out the circuit neatly with jumper wires.

2. **Upload the code:**
   - Open the Arduino IDE.
   - Copy or write your sketch with distance detection logic.
   - Select your board and port.
   - Click **Up**
