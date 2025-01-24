# Smart Security System 🔒

## 📖 Overview
The Smart Security System is an IoT-based home security solution designed to enhance safety using facial recognition and automation. This project integrates hardware components like Raspberry Pi with Python scripts to detect and recognize faces, making it an innovative and reliable security tool for modern homes.

## 🎯 Objectives
- Detect and recognize faces using a Raspberry Pi and camera module.
- Automate alerts and responses upon identifying authorized or unauthorized individuals.
- Enhance home security with real-time face recognition and response mechanisms.

---

## 🛠️ Key Features

### 🔍 Face Detection and Recognition
- Utilizes Haar Cascade Classifiers for face detection.
- Implements a facial recognition algorithm to identify authorized users.

### ✨ Data Management
- Includes a `create_data.py` script to capture and store face data for training.
- Stores and processes images to build a robust facial recognition model.

### 🎨 Real-Time Monitoring
- Captures live video feed using a Raspberry Pi camera.
- Identifies individuals in real-time and triggers appropriate actions.

### 🚨 Automated Alerts
- Sends notifications or triggers alarms upon detecting unauthorized access.
- Option to integrate with additional IoT devices for enhanced automation.

---

## 🧰 Tools & Technologies
- **Hardware**: Raspberry Pi, Pi Camera, Servo Motor
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy

---

## 🚀 How to Use

1. **Setup**:
   - Install Python and required libraries on Raspberry Pi.
   - Connect the Pi Camera and other components as per the circuit diagram.
2. **Train Data**:
   - Use `create_data.py` to capture images of authorized individuals.
3. **Run System**:
   - Execute `face_recognize.py` for real-time face recognition and alerts.
4. **Optional Automation**:
   - Use `servo_raspi.py` to control a servo motor for additional security mechanisms (e.g., locking/unlocking doors).

---

## 🎨 Results
- **Real-Time Detection**: Accurately detected and recognized faces in live feeds.
- **Enhanced Security**: Triggered automated responses for unauthorized access.
- **Scalable Solution**: Can be extended to include additional IoT integrations.

---

## 📁 Repository Structure
```
|-- data/                     # Training data and captured images
|-- scripts/                  # Python scripts for detection and automation
|-- README.md                 # Project overview and usage guide
|-- face_recognize.py         # Main script for facial recognition
|-- create_data.py            # Script to capture training data
|-- servo_raspi.py            # Servo motor control script
```

---

## 📩 Contact
For questions or collaboration:

**Name**: Vamshi Krishna Perabathula  
**Email**: [v_perabathula@u.pacific.edu](mailto:v_perabathula@u.pacific.edu)  
**LinkedIn**: [Vamshi Krishna Perabathula](https://www.linkedin.com/in/vk-perabathula/)
