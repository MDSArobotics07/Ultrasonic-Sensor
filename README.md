# Ultrasonic Sensor Project 🦇📏

This Ultrasonic Sensor project uses echolocation—like a bat—to measure distance, detect motion, and trigger responses. Using an ultrasonic sensor, it emits sound waves and listens for echoes to determine how far away an object is. Depending on the distance, it can light up an RGB LED, play a sound with a piezo buzzer, or respond to a push button input. It’s a great way to explore how sensors interact with output components in real time.

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

### 1. Build the Circuit

#### Ultrasonic Sensor:
- VCC → 5V  
- GND → GND  
- Trig → Digital Pin (e.g., 9)  
- Echo → Digital Pin (e.g., 10)  

#### RGB LED:
- Connect each leg (R, G, B) through a resistor to PWM digital pins (e.g., 3, 5, 6)  
- Common cathode/anode → GND or 5V accordingly  

#### Piezo Buzzer:
- Positive → Digital Pin (e.g., 8)  
- Negative → GND  

#### Push Button:
- One leg → Digital Pin (e.g., 2)  
- Other leg → GND (with pull-down resistor setup)

#### Layout:
- Use a breadboard to organize everything and jumper wires for connections.

### 2. Upload the Code

- Open the Arduino IDE.
- Copy or write your sketch with distance detection and output response logic.
- Select the correct board and COM port.
- Click **Upload** to program your Arduino.

---

## 💡 How It Works

1. The ultrasonic sensor sends out a sound pulse.
2. It waits for the echo to bounce back from an object.
3. The Arduino calculates the distance based on the time taken for the echo.
4. Based on the distance:
   - The RGB LED changes color (e.g., red when close, green when far).
   - The piezo buzzer can sound an alert for nearby objects.
   - The push button can toggle features or trigger modes.

---

## 🖼️ Circuit Board Overview

Here’s what the setup looks like on a breadboard:

<img width="1440" height="715" alt="Ultrasonic Sensor 4-pin" src="https://github.com/user-attachments/assets/1b60ddc4-0d02-455d-8ec8-fecde119762f" />


---

## 🔗 Simulation Links

- [Tinkercad Simulation](https://www.tinkercad.com/)  
*Include your specific simulation link here if available.*

---

## 🙌 Credits

**Created by:** Zahara BG  
Inspired by nature’s echolocation and basic obstacle detection systems.
