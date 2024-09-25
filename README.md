# 🚦 Arduino-Based 4-Way Traffic Signal Simulation

Welcome to the **4-Way Traffic Signal Simulation** project! This educational project is designed to demonstrate how a traffic light control system works using fundamental concepts of Computer Organization and Architecture. By utilizing an Arduino Mega 2560, LEDs, resistors, and the Arduino IDE, we simulate a traffic light system for a 4-way intersection, offering practical insights into how microcontrollers manage traffic flow.

## 🧠 **Why This Project Matters**

Understanding how microcontrollers control traffic signals helps illustrate the fundamentals of computer architecture, input/output management, and timing control in embedded systems. This project provides a hands-on experience with basic concepts of electronics and control systems, offering a simplified but effective way to grasp how more complex, real-world systems function.

---

## 🎯 **Project Objectives**

- **Simulate a 4-way traffic light** using Arduino Mega 2560 to manage lane transitions and signal timings.
- **Demonstrate microcontroller-based control** using LEDs to replicate red, yellow, and green traffic lights.
- **Understand I/O control** by interfacing LEDs with Arduino pins.
- **Learn the principles of traffic management** through this small-scale simulation.

---

## 🔧 **Components Used**

- **Arduino Mega 2560**: The microcontroller serving as the "brain" of the traffic signal system.
- **Red, Yellow, and Green LEDs** (4 of each): Represent the traffic lights for the four lanes.
- **220-ohm Resistors** (12 pieces): Protect the LEDs from excessive current.
- **Jumper Cables**: Connect components on the breadboard.
- **Breadboards**: Serve as the base for assembling the circuit connections.

---

## 📜 **How It Works**

The Arduino-based system manages the traffic lights for a 4-way intersection using a predefined sequence:
1. **Lane 1** receives a green light while other lanes display red.
2. After a set duration (e.g., 7 seconds), **Lane 1** transitions from green to yellow, signaling a change.
3. **Lane 2** then receives the green light while **Lane 1** shifts to red.
4. The process repeats for **Lanes 3** and **4** in a similar manner, creating a full traffic cycle.
5. The system continuously loops, simulating an ongoing traffic flow.

![Working 2](./screenshots/Working2.png)

![Working 3](./screenshots/Working3.png)

---

## 💡 **Control Signals**

- **Red Light**: Indicates "STOP" for vehicles.
- **Yellow Light**: Acts as a caution, signaling "WAIT" or "GET READY."
- **Green Light**: Grants permission to "GO."

---

## 🔍 **Block Diagram Overview**

- A total of 12 LEDs are used, with 3 LEDs per lane (red, yellow, and green).
- Each LED is connected to the Arduino through a 220-ohm resistor to prevent excess current flow, ensuring safe operation.

![Block Diagram](./screenshots/Block.png)

---

## 🎓 **Educational Value**

- **Understanding Traffic Control**: Gain insights into how real-world traffic signals are managed through a simple timing algorithm.
- **Microcontroller Fundamentals**: Learn how to program and control the Arduino for managing LEDs based on specific intervals.
- **I/O Management**: Experience interfacing output devices (LEDs) with a microcontroller using basic circuitry.

---

## ⚙️ **Expected Outcome**

- A functioning 4-way traffic signal simulation demonstrating proper red, yellow, and green light sequences for all four lanes.
- A practical understanding of how microcontrollers execute control tasks using timing and I/O management, providing foundational knowledge for more advanced traffic control systems.

![Expected Outcome](./screenshots/Outcome.png)

---

## 👩‍💻 **Author**

- **Khushi Goel** - [GitHub Profile](https://github.com/khushigoel)

---

## 🔗 **References**

1. [Introduction to Arduino](https://www.arduino.cc/)
2. [Traffic Light Control System Basics](https://en.wikipedia.org/wiki/Traffic-light_control_and_coordination)

Feel free to replicate, experiment, or expand upon this project to gain further insights into traffic control and microcontroller applications! 🚥
