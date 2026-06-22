# Next-Generation Patient Caring System

## 📌 Overview
The Next-Generation Patient Caring System is a vision-based healthcare assistance solution designed to help patients who are unable to feed themselves independently. The system uses computer vision techniques to detect the patient's mouth position in real time. When the mouth is detected as open, an Arduino-controlled water pump automatically dispenses water through a feeding pipe, providing a safe and contactless feeding mechanism.

---

## 🚀 Features
- Real-time mouth detection using computer vision
- Automated water dispensing based on mouth position
- Arduino-based motor control
- Contactless and user-friendly operation
- Seamless hardware and software integration
- Assistive healthcare application

---

## 🛠️ Tech Stack

### Software
- Python
- OpenCV
- MediaPipe
- Arduino IDE

### Hardware
- Arduino Uno
- Motor Shield
- Camera/Webcam
- Submersible Water Pump
- 7.4V Battery
- USB Type-C Cable
- Feeding Pipe

---

## ⚙️ System Workflow

1. Capture real-time video using a camera.
2. Detect facial landmarks and monitor mouth position.
3. Determine whether the mouth is open or closed.
4. Send a signal to the Arduino when the mouth is open.
5. Activate the motor shield and water pump.
6. Dispense water through the feeding pipe.
7. Stop the pump automatically when the mouth closes.

---

## 🏗️ System Architecture

```text
Camera/Webcam
      │
      ▼
Mouth Detection
(OpenCV + MediaPipe)
      │
      ▼
Arduino Uno
      │
      ▼
Motor Shield
      │
      ▼
Submersible Water Pump
      │
      ▼
Feeding Pipe
      │
      ▼
Patient
```

## 🎯 Objectives

- Assist patients with limited mobility.
- Automate the feeding process using computer vision.
- Reduce caregiver workload.
- Provide a safe and contactless healthcare solution.
- Demonstrate hardware–software integration in healthcare applications.

---

## 📈 Future Scope

- Integration with IoT for remote monitoring.
- Mobile application support.
- Voice-controlled feeding assistance.
- Enhanced low-light detection using infrared cameras.
- AI-based adaptive feeding mechanisms.

---

## 💡 Key Highlights

- Vision-based patient assistance system
- Real-time mouth detection
- Automated water feeding mechanism
- Computer Vision + Embedded Systems integration
- Cost-effective healthcare automation solution

---

## 👨‍💻 Author

**Sameena Kausar Magami**

Final Year Project – Next-Generation Patient Caring System

---

⭐ If you found this project interesting, consider giving it a star!
