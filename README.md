**Next-Generation Patient Caring System**

**📌 Overview**

The Next-Generation Patient Caring System is a vision-based healthcare assistance solution designed to help patients who have difficulty feeding themselves. The system uses computer vision to detect the patient's mouth position in real time. When the mouth is detected as open, an Arduino-controlled water pump automatically dispenses water through a feeding pipe, providing a safe and contactless feeding mechanism.

**🚀 Features**

Real-time mouth detection using computer vision

Automated water dispensing based on mouth position

Arduino-based motor control

Contactless and user-friendly operation

Integration of software and hardware components

Suitable for assistive healthcare applications


**🛠️ Technologies Used**
Python
OpenCV
MediaPipe
Arduino
Arduino IDE
Computer Vision
Embedded Systems

**🔧 Hardware Components**
Arduino Uno
Motor Shield
Submersible Water Pump
USB Type-C Cable
7.4V Battery
Camera/Webcam
Feeding Pipe

**⚙️ System Workflow**
Camera captures real-time video of the patient.
MediaPipe detects facial landmarks and monitors mouth position.
The system determines whether the mouth is open or closed.
When the mouth is open, a signal is sent to the Arduino.
Arduino activates the motor shield and water pump.
Water is delivered through the feeding pipe.
The pump stops automatically when the mouth closes.

**📊 Project Architecture**
Camera
   │
   ▼
Mouth Detection
(OpenCV + MediaPipe)
   │
   ▼
Arduino Microcontroller
   │
   ▼
Motor Shield
   │
   ▼
Submersible Water Pump
   │
   ▼
Patient Feeding

**🎯 Objectives**
Assist patients with limited mobility.
Reduce caregiver intervention during feeding.
Provide a safe and automated feeding mechanism.
Demonstrate integration of computer vision and embedded systems.

**📈 Future Enhancements**
Voice-controlled feeding assistance.
Mobile application integration.
IoT-based remote monitoring.
Improved AI-based patient interaction.
Low-light detection using infrared cameras.

**👨‍💻 Author**

[**Sameena Kausar Magami**]
Final Year Project – Next-Generation Patient Caring System

⭐ If you found this project useful, consider giving it a star on GitHub!
