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
   - Click **Upload** to load the program onto your Arduino.

---

## 💡 How It Works

- The **ultrasonic sensor** sends out a high-frequency sound wave.
- It waits for the echo to return after bouncing off an object.
- The Arduino calculates the time taken and converts it to distance.
- Depending on the distance:
  - The **RGB LED** changes color (e.g., red for near, green for far).
  - The **piezo buzzer** can beep when objects are very close.
  - The **push button** can be used to turn features on or off, or trigger additional modes.

---

## 🖼️ Images / Videos

> *(Add your own media showing your working prototype here.)*  
Suggested:
- `images/ultrasonic-circuit.jpg`
- `videos/distance-detection-demo.mp4`

---

## 🔗 Simulation Links

- [Tinkercad Simulation (if available)](https://www.tinkercad.com/)  
> *Add your custom simulation link if you've tested or built this online.*

---

## 🙌 Credits

**Created by:** Zahara BG  
