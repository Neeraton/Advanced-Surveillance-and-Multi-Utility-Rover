# Advanced Surveillance and Multi-Utility Rover

Advanced Surveillance and Multi-Utility Rover
A rugged, camera-equipped robotic rover designed for real-time surveillance, autonomous navigation, and multi-terrain mobility.


This project showcases the design and development of a 6-wheeled rocker-bogie rover equipped with surveillance and image processing capabilities. The rover is capable of operating in both autonomous and manual modes. It is integrated with a camera system, motion control, and real-time object detection models, making it suitable for security, inspection, and exploration tasks. The rover can be remotely monitored and controlled via a web interface and is powered by a Raspberry Pi.




![img1_group](https://github.com/user-attachments/assets/d93624eb-7d6e-4c72-b1db-0686d0a80e97)


## 📌 Key Highlights

* 🚙 **Rocker-Bogie Mobility System**
  Stable and adaptable movement across rocky and uneven terrains.

* 🎥 **Pan-Tilt Camera Surveillance**
  Real-time video feed with remote directional control.

* 🧠 **AI-Powered Image Processing**

  * Object detection
  * Face recognition
  * Gesture recognition


![object](https://github.com/user-attachments/assets/07cc9407-5fb1-4fd3-990c-e86db6aeb464)


* 🌐 **Web Interface for Control**
  Easy-to-use dashboard for monitoring and remote operation.


![web](https://github.com/user-attachments/assets/b5c53126-309b-4f4a-974a-825e107159af)


* 🧭 **Autonomous Navigation (Optional)**
  Vision-based movement and obstacle avoidance.

---

## 🔧 Hardware Components

* Raspberry Pi 4B (4GB)
* Pi Camera Module
* 6 × DC Motors with encoders
* Motor Driver (L298N or equivalent)
* Servo motors for pan-tilt system
* 3D-printed Rocker-Bogie chassis (PLA)
* Li-ion battery pack or power bank
* (Optional) Solar panel for outdoor support

---

## 💻 Software and Tools

* **Language:** Python
* **Libraries:** OpenCV, TensorFlow/Keras, Flask, RPi.GPIO
* **Framework:** Flask (for live stream + control panel)
* **Streaming:** MJPEG/WebRTC
* **Control Logic:** Manual and autonomous

---

## 🗂️ Repository Structure

```
/advanced-surveillance-rover
│
├── /models/               → Pre-trained AI models
├── /hardware/             → Schematics, wiring, 3D files
├── /camera_stream/        → Flask-based video stream code
├── /rover_control/        → Motor control and movement logic
├── /navigation/           → Obstacle detection & auto-mode
├── /web_interface/        → HTML/CSS dashboard for remote control
├── /images/               → Sample outputs/screenshots
└── README.md
```

![system](https://github.com/user-attachments/assets/82406aa1-1070-42f8-a375-50f7a9ab69fd)


---

## 🚀 Getting Started

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/advanced-surveillance-rover.git
   cd advanced-surveillance-rover
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Start the rover’s web interface:**

   ```bash
   python3 app.py
   ```

4. **Access via browser:**

   ```
   http://<raspberry-pi-ip>:5000
   ```

---

## 🧪 Field Testing

* ✅ Operated on rocky, tiled, and sandy terrain
* 📡 Live video tested up to 20 meters range
* 🕒 < 1s average delay in video + control feedback

---

## 🛠️ Applications

* 🔍 Border and military surveillance
* 🏭 Industrial inspection
* 🌾 Agriculture field monitoring
* 🚧 Disaster response zones
* 🎓 Academic and research labs

---

## 📸 Sample Previews


![com](https://github.com/user-attachments/assets/4ada4900-28f4-4812-91b3-202be8aa56a3)


---

## 👥 Team Members

* **Neeraj Chaurasia**
  🔗 [https://github.com/Neeraton](https://github.com/Neeraton)

* **Pratik Chauhan**
  🔗 [https://github.com/PR4TIK04](https://github.com/PR4TIK04)

* **Mojes Dhotre**
  🔗 [https://github.com/M0J3S](https://github.com/M0J3S)

---

