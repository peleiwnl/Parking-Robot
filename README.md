# 🚗 Autonomous Parking Robot (mBot2)

This project showcases a fully autonomous parking robot system developed using the **mBot2** and programmed in **Python**. The robot simulates a real-world self-parking car, utilizing mBot2’s full sensor suite and hardware capabilities to navigate a car park, detect parking spaces, and respond to real-time environmental inputs.

---

## 🎯 Project Objective

To build an intelligent autonomous robot that:
- Navigates a custom car park layout using line-following.
- Identifies and occupies valid parking spaces.
- Responds to obstacles, environmental stimuli, and priority protocols.
- Simulates realistic car functionalities such as indicators, brake lights, and emergency responses.

---

## 🧠 Key Features

### 🚗 Line Following
- Implemented with a **Quad-RGB sensor**.
- Adjusts steering using outer and inner probes for smooth and sharp turns.
- Includes robust calibration and debugging tools.

### 🅿️ Autonomous Parking
- Detects parking zones via color changes.
- Uses an **Ultrasonic sensor** to determine if a space is available.
- Executes safe parking maneuvers or continues if space is occupied.

### ⚙️ Realistic Car Functionality
- **Indicators & Brake Lights:** Controlled via rear LEDs.
- **Headlights:** Activated in low light using the **Light Sensor**.
- **Reverse Lights:** Engaged when backing up.
- **Car Horn:** Beeps when blocked by obstacles.

### 🔒 Security & Emergency
- **Car Alarm:** Triggered by the **Motion Sensor** when excessive motion is detected while parked.
- **Emergency Mode:** Uses the **Microphone** to detect the keyword "emergency" and immediately exits the car park.

### 🧾 Priority Parking
- Uses **Wi-Fi LAN communication** to simulate a payment system.
- Grants extended parking time if authenticated.

### 🔍 Debugging Tools
- Real-time display of sensor input for testing and calibration.
- Onboard monitoring for RGB color values and distance readings.

---

## 📦 Hardware Used

- **Quad-RGB Sensor** – Line detection and color-coded parking zones.
- **Ultrasonic Sensor** – Object detection and space validation.
- **Light Sensor** – Headlight control in low-light conditions.
- **Motion Sensor** – Detects unexpected movement (simulated theft).
- **Speaker & Microphone** – Horn and emergency detection.
- **LEDs** – Simulate brake, reverse, headlight, and indicator lights.
- **Wi-Fi Module** – LAN-based communication for priority parking.

---

## 🧑‍💻 Software Design Highlights

- Python code structured into modular functions (line following, parking, alarms, etc.)
- Sensor integration for real-time adaptive behavior.
- Event-based triggers for emergency, alarms, and interactions.

---

## 🧪 Testing & Debugging

- Calibrated sensors with live visual feedback.
- Isolated component testing (e.g., RGB probe behavior, ultrasonic range).
- Verified complex sequences like reversing out of a full lot or emergency handling.

---

## 🗺️ Car Park Layout

- Designed a physical map to simulate a realistic parking scenario.
- Parking spaces color-coded for standard, disabled, and electric-only zones.
- Navigation routes do not rely on hard-coded paths — robot adapts dynamically.

---

## 🏁 Final Thoughts

This project demonstrated the potential of combining robotics hardware with intelligent software to simulate a real-world autonomous parking system. It served as a practical introduction to:
- Robotics control systems
- Sensor integration
- Autonomous decision-making

---

