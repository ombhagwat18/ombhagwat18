<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Bhagwat%20Om%20Dilip&fontSize=60&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Robotics%20%7C%20AI%20%7C%20Computer%20Vision%20%7C%20Industrial%20Automation&descAlignY=55&descSize=18"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3000&pause=800&color=00C2FF&center=true&vCenter=true&multiline=false&repeat=true&width=750&height=60&lines=🤖+Building+Intelligent+Industrial+Robots;🧠+AI+%2B+Computer+Vision+%2B+ROS+2;⚙️+PLC+%7C+SCADA+%7C+Industrial+Automation;🔬+Turning+Ideas+Into+Real+Working+Robots;🚀+Final+Year+Robotics+%26+Automation+Engineer" alt="Typing SVG" />
</a>

<br/>

<!-- Social Badges -->
<p>
  <a href="https://linkedin.com/in/ombhagwat18">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0077B5" />
  </a>
  <a href="mailto:YOUR_EMAIL">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/YOUR_USERNAME">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge&color=00C2FF&label=PROFILE+VIEWS" />
</p>

---

</div>

## 🧠 About Me — The Engineer Behind the Machines

```python
class RoboticsEngineer:
    def __init__(self):
        self.name            = "Bhagwat Om Dilip"
        self.role            = "Robotics & Automation Engineer | AI/ML Developer"
        self.college         = "K.K. Wagh Institute of Engineering, Nashik"
        self.degree          = "B.Tech — Robotics & Automation Engineering (Final Year)"
        self.location        = "Nashik, Maharashtra, India 🇮🇳"
        self.languages       = ["Python", "C++", "JavaScript", "LADDER (PLC)"]
        self.mission         = "Build intelligent machines that solve real industrial problems"

    def current_focus(self):
        return [
            "🔬 Industrial AI & Vision-Guided Robotics",
            "⚙️  PLC/SCADA Integration with AI Systems",
            "🤖 ROS 2 + MoveIt2 + Yaskawa GP12 Arm",
            "📷 YOLOv8 Real-Time Defect Detection",
            "🧠 Deep Learning & Edge AI Deployment",
            "🌐 Industrial IoT Dashboard Development",
        ]

    def philosophy(self):
        return "Engineering is turning 'what if?' into 'it works.'"

me = RoboticsEngineer()
print(me.philosophy())
# Output: Engineering is turning 'what if?' into 'it works.'
```

---

## 🏭 Professional Summary

<div align="center">

| 🎯 Domain | 💡 Expertise | 🔧 Tools |
|---|---|---|
| **Industrial Robotics** | 6-DOF Arms, Pick & Place, Motion Planning | Yaskawa GP12, ROS 2, MoveIt2, MotoROS2 |
| **Computer Vision** | Object Detection, Defect Inspection, ArUco | YOLOv8, OpenCV, Intel RealSense D455 |
| **Industrial Automation** | PLC Programming, SCADA, HMI Design | Delta DVP, Siemens, Schneider, KEPServerEX |
| **Embedded Systems** | Firmware, Real-Time Control, IoT Gateways | ESP32, Raspberry Pi, Arduino, UART/SPI/I2C |
| **AI / ML** | Training Pipelines, Inference, Edge Deploy | PyTorch, TensorFlow, ONNX, CUDA |
| **Web Dashboards** | Industrial HMI-like Monitoring UIs | Flask, HTML/CSS/JS, WebSockets, SSE |

</div>

---

## 🚀 Flagship Projects

<details open>
<summary><b>🍾 Smart Bottle Inspection System — BottleGuardPro</b></summary>

> **Real-time AI-powered defect detection on a Bisleri bottle conveyor line**

- 📷 **Vision**: Dual EMEET 4K cameras + LED lighting in custom detection chamber
- 🧠 **AI Engine**: YOLOv8 trained on custom dataset with 50+ defect classes (LAB color-space calibrated)
- ⚙️ **PLC Integration**: Delta DVP14SS via RS-232 Modbus RTU — conveyor + pneumatic rejection actuator control
- 📊 **Dashboard**: Live monitoring, SPC control charts, analytics, false-positive feedback loop for retraining
- 🏗️ **Hardware**: Custom fabricated metal enclosure (C-bend body, door panel)
- 🔗 **Stack**: Python · OpenCV · YOLOv8 · Flask · PyQt5 · Delta PLC · ESP32

</details>

<details>
<summary><b>🤖 Vision-Guided Pick & Place — Yaskawa GP12 (Internship @ Armstrong Dematic)</b></summary>

> **Autonomous industrial robot arm with AI vision for intelligent pick-and-place**

- 🦾 **Robot**: Yaskawa Motoman GP12 (6-DOF, 12 kg payload) via YRC1000 Controller + MotoROS2
- 📷 **Perception**: Intel RealSense D455 for depth-based 3D pose estimation + ArUco marker detection
- 🧭 **Planning**: ROS 2 Humble + MoveIt2 + custom URDF/SRDF with corrected DH parameters
- 🎯 **Object Detection**: YOLOv8 for target identification with vision-to-robot coordinate transforms
- 🔬 **Simulation**: Gazebo + RViz2 offline development with ROS bag playback
- 📄 **Output**: Full academic/industrial project report + IEEE-format literature review

</details>

<details>
<summary><b>🌱 Autonomous Weed Detection & Agricultural Robot</b></summary>

> **Raspberry Pi robot for soybean field weed cutting + water spraying**

- 🎯 **Detection**: PiCamera2-based weed identification
- ⚙️ **Actuation**: L298N motor driver + relay-controlled weed cutter + water pump
- 🌐 **Control**: Flask web dashboard with live camera feed + GPIO control

</details>

<details>
<summary><b>🛣️ AI Pothole Detection & Canal Inspection (Autoscanx)</b></summary>

> **ESP32-based autonomous inspection vehicle with PyQt5 GUI and MJPEG stream**

- 📡 **Streaming**: Live MJPEG video over WiFi parsed in real-time
- 🖥️ **GUI**: PyQt5 desktop app with map overlay and defect logging
- 🤖 **Detection**: Computer vision pipeline for pothole / surface anomaly classification

</details>

<details>
<summary><b>🐾 Dog Daycare Automation System</b></summary>

> **Raspberry Pi Zero W smart automation with real-time SSE web dashboard**

- 🌐 **Backend**: Flask + GPIO servo/pump control
- 📊 **Dashboard**: Real-time Server-Sent Events (SSE) based monitoring UI

</details>

---

## 🛠️ Full Tech Stack

### 💻 Programming Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,js,html,css,bash" />
</p>

---

### 🤖 Robotics & ROS Ecosystem

<p>
  <img src="https://skillicons.dev/icons?i=ros" />
</p>

| Tool | Purpose |
|---|---|
| **ROS 2 Humble** | Middleware, node architecture, topics, services, actions |
| **MoveIt2** | Motion planning, collision avoidance, trajectory execution |
| **Gazebo / Ignition** | Physics simulation & URDF testing |
| **RViz2** | 3D visualization & debugging |
| **MotoROS2** | Yaskawa GP12 real-robot driver via YRC1000 |
| **SLAM / Nav2** | Mapping and autonomous navigation |
| **URDF / SRDF** | Robot model definition with correct DH parameters |
| **Intel RealSense SDK** | D455/D435 depth camera integration |

---

### 🧠 AI & Machine Learning

<p>
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv" />
</p>

| Library | Use Case |
|---|---|
| **YOLOv8 (Ultralytics)** | Real-time object detection & defect classification |
| **OpenCV** | Image processing, ArUco detection, color calibration |
| **PyTorch / TensorFlow** | Model training, fine-tuning, transfer learning |
| **NumPy / Pandas** | Data pipelines, dataset management |
| **Matplotlib / Seaborn** | Analytics visualization, SPC charts |
| **ONNX / TensorRT** | Edge AI model optimization |

---

### ⚙️ Industrial Automation — PLC · SCADA · HMI

```
┌─────────────────────────────────────────────────────────────────┐
│                   INDUSTRIAL AUTOMATION STACK                   │
├──────────────────┬──────────────────┬───────────────────────────┤
│   PLC BRANDS     │   PROTOCOLS      │   SCADA / HMI             │
│                  │                  │                           │
│  • Delta DVP     │  • Modbus RTU    │  • Wonderware InTouch     │
│  • Siemens S7    │  • Modbus TCP    │  • KEPServerEX OPC        │
│  • Schneider     │  • RS-232/485    │  • Custom Web HMI (Flask) │
│                  │  • Profibus      │  • Real-time Dashboards   │
├──────────────────┼──────────────────┼───────────────────────────┤
│   PROGRAMMING    │   HARDWARE       │   STANDARDS               │
│                  │                  │                           │
│  • Ladder (LAD)  │  • Conveyors     │  • IEC 61131-3            │
│  • FBD           │  • Actuators     │  • ISA-88 / ISA-95        │
│  • ST            │  • Solenoids     │  • OPC-UA                 │
│  • SFC           │  • Pneumatics    │  • Industry 4.0           │
└──────────────────┴──────────────────┴───────────────────────────┘
```

---

### 🔌 Embedded Systems & Electronics

<p>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

| Platform | Protocols | Applications |
|---|---|---|
| **ESP32** | WiFi, BLE, UART, SPI, I2C | IoT gateways, dashboards, robot controllers |
| **Raspberry Pi 4/ZeroW** | GPIO, CSI, USB | Vision systems, Flask servers, edge AI |
| **Arduino Mega/Nano** | UART, I2C, PWM | Sensor fusion, servo control, prototyping |
| **Communication** | RS-232, RS-485, Modbus, CAN | PLC ↔ PC industrial integration |
| **Sensors** | IMU, Ultrasonic, DHT, Encoders | Mobile robots, safety systems |
| **Actuators** | Servo, Stepper, DC, Pneumatic | Grippers, conveyors, cutters |

---

### 🖥️ CAD & Design Tools

<p align="left">
  <img src="https://img.shields.io/badge/SolidWorks-FF0000?style=for-the-badge&logo=solidworks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Fusion%20360-FF6900?style=for-the-badge&logo=autodesk&logoColor=white"/>
  <img src="https://img.shields.io/badge/AutoCAD-E51050?style=for-the-badge&logo=autocad&logoColor=white"/>
  <img src="https://img.shields.io/badge/BricsCAD-1565C0?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/TinkerCAD-1477D1?style=for-the-badge&logo=autodesk&logoColor=white"/>
</p>

> Enclosure fabrication drawings, robot cell layouts, sheet metal C-bend designs, URDF mesh modeling

---

### 🔧 Dev Tools & Platforms

<p>
  <img src="https://skillicons.dev/icons?i=vscode,git,github,linux,bash,docker" />
</p>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00C2FF&icon_color=00C2FF&text_color=ffffff"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C2FF&text_color=ffffff"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&background=0D1117&stroke=00C2FF&ring=00C2FF&fire=FF6B35&currStreakLabel=00C2FF&sideLabels=ffffff&dates=888888"/>

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=algolia&no-frame=true&no-bg=true&row=1&column=7"/>
</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&bg_color=0D1117&color=00C2FF&line=00C2FF&point=FF6B35&area=true&hide_border=true"/>
</div>

---

## 🎓 Education & Certifications

<div align="center">

| 🏫 | Institution | Degree / Certification | Status |
|---|---|---|---|
| 🎓 | K.K. Wagh Institute, Nashik | B.Tech — Robotics & Automation Engineering | 🟡 Final Year |
| 🤖 | Coursera / DeepLearning.AI | Machine Learning Specialization | ✅ Certified |
| 🧠 | Google / Coursera | Generative AI Fundamentals | ✅ Certified |
| ⚙️ | Industrial Training | PLC & SCADA Programming | ✅ Certified |
| 🤖 | The Construct / Udemy | ROS & ROS 2 Development | ✅ Certified |
| 🔌 | Embedded Systems | Arduino, ESP32, Raspberry Pi | ✅ Certified |

</div>

---

## 💼 Experience Timeline

```
2024 ──────── Armstrong Dematic, Nashik
               🤖 Automation & Robotics Intern
               └─ Vision-Guided GP12 Pick & Place | ROS2 | MoveIt2 | MotoROS2

2023-24 ────── Industrial Projects
               ⚙️  BottleGuardPro — AI Inspection System
               └─ YOLOv8 | Delta PLC | OpenCV | Flask Dashboard

2023 ──────── Software Developer Intern
               🌐 Codephoton — IoT Garbage Van Monitoring System
               └─ ESP32 | Web Dashboard | Real-time Telemetry

2022-23 ────── Competition & Research
               🏁 Roborace Competitions — ESP32 Robot Cars
               🛣️  Autoscanx — Pothole & Canal Inspection Robot
               🌱 Agricultural Robot — Weed Detection & Spraying
```

---

## 🌐 Domain Knowledge Map

```
                        ┌─────────────────────┐
                        │    INDUSTRIAL AI    │
                        │  YOLOv8 · OpenCV    │
                        │  Edge Inference     │
                        └──────────┬──────────┘
                                   │
            ┌──────────────────────┼──────────────────────┐
            │                      │                      │
┌───────────▼──────────┐ ┌────────▼────────┐ ┌──────────▼───────────┐
│  INDUSTRIAL ROBOTICS │ │   AUTOMATION    │ │  EMBEDDED SYSTEMS    │
│  ROS 2 · MoveIt2    │ │  PLC · SCADA    │ │  ESP32 · RPi · AVR   │
│  GP12 · 6-DOF Arms  │ │  HMI · Modbus   │ │  UART · SPI · I2C    │
│  Gazebo Sim · RViz  │ │  Delta/Siemens  │ │  FreeRTOS · GPIO     │
└───────────┬──────────┘ └────────┬────────┘ └──────────┬───────────┘
            │                      │                      │
            └──────────────────────┼──────────────────────┘
                                   │
                        ┌──────────▼──────────┐
                        │   IoT DASHBOARDS    │
                        │  Flask · WebSocket  │
                        │  SSE · HTML/CSS/JS  │
                        └─────────────────────┘
```

---

## 🏅 Competitions & Achievements

- 🏁 **Roborace** — Autonomous/Manual robot car competition (ESP32 + custom chassis)
- 🤖 **Robotics Workshops** — Organized and participated in hands-on robotics sessions
- 🏆 **Industrial Automation Projects** — Real-world PLC + AI integration at production scale
- 🎯 **Internship** — Selected for Automation Department at Armstrong Dematic, Nashik

---

## 💬 What Drives Me

<div align="center">

> *"I don't just study robotics — I build it.*
> *Every project is a step toward machines that think, see, and act intelligently in the real world."*

**— Bhagwat Om Dilip**

</div>

---

<div align="center">

<!-- Footer Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling"/>

**⭐ If you find my work interesting, drop a star on my repos!**

*Always open to collaborations in Robotics, AI, and Industrial Automation.*

</div>
