<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:0A0E14,50:1A1206,100:0A0E14&height=260&section=header&text=OM%20DILIP%20BHAGWAT&fontSize=56&fontColor=FFB020&animation=fadeIn&fontAlignY=38&desc=ROBOTICS%20%26%20AUTOMATION%20ENGINEER&descAlignY=58&descSize=20&descColor=E6E6E6"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2400&pause=600&color=FFB020&center=true&vCenter=true&width=900&height=40&lines=Deploying+Vision-Guided+Robots+on+Real+Production+Lines;ROS+2+%C2%B7+MoveIt2+%C2%B7+MotoROS2+%C2%B7+Yaskawa+GP12;YOLOv8+%2B+OpenCV+%2B+TensorRT+Edge+Inference;PLC+%C2%B7+SCADA+%C2%B7+Modbus+RTU%2FTCP+Integration;From+CAD+to+Code+to+Conveyor+-+Full+Stack+Robotics" alt="Typing SVG"/>
</a>

<br/>

<img src="https://img.shields.io/badge/●-OPEN_TO_WORK-1E1E1E?style=flat-square&labelColor=1E1E1E&color=3DDC97&logoColor=3DDC97" height="26"/>
<img src="https://img.shields.io/badge/B.Tech_Robotics_%26_Automation-Final_Year-1E1E1E?style=flat-square&labelColor=1E1E1E&color=FFB020" height="26"/>
<img src="https://komarev.com/ghpvc/?username=ombhagwat18&style=flat-square&color=FFB020&label=PROFILE+VIEWS&labelColor=1E1E1E" height="26"/>

<br/><br/>

<a href="https://linkedin.com/in/ombhagwat18"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ombhagwat18@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/ombhagwat18"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

<table>
<tr>
<td width="60%" valign="top">

### ⚙️ System Manifest

```yaml
engineer:
  designation : Robotics & Automation Engineer
  institution : K.K. Wagh Institute of Engineering, Nashik
  degree      : B.Tech, Robotics & Automation (Final Year)
  based_in    : Nashik, Maharashtra, IN

  domains:
    - Industrial Robotics        → ROS 2 · MoveIt2 · MotoROS2
    - Machine Vision             → YOLOv8 · OpenCV · RealSense
    - PLC / SCADA Automation     → Delta DVP · Siemens S7 · Modbus
    - Edge AI Deployment         → ONNX · TensorRT
    - Mechanical Design          → SolidWorks · Fusion 360

  currently_building : >
    AI inspection + robotic pick-place systems that run
    unattended on real conveyor lines, not just in Gazebo.

  status : ONLINE — evaluating Robotics / CV / Automation roles
```

</td>
<td width="40%" valign="top" align="center">

<img src="https://media.giphy.com/media/VYRXfjcnW8ULe8Fq3q/giphy.gif" width="270"/>
<br/>
<sub>6-DOF industrial arm — same class I program daily</sub>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=ombhagwat18&show_icons=true&hide_title=true&hide_border=true&bg_color=00000000&title_color=FFB020&icon_color=FFB020&text_color=E6E6E6&hide_rank=false" width="100%"/>

</td>
</tr>
</table>

---

## 🏭 Engineering Domains

<div align="center">

<table>
<tr>
<th>Domain</th><th>What I Do</th><th>Stack</th>
</tr>
<tr>
<td><b>🦾 Industrial Robotics</b></td>
<td>6-DOF motion planning, inverse kinematics, kinematic tree design</td>
<td><code>Yaskawa GP12</code> <code>ROS 2 Humble</code> <code>MoveIt2</code> <code>MotoROS2</code></td>
</tr>
<tr>
<td><b>👁️ Machine Vision</b></td>
<td>Real-time defect detection, ArUco pose estimation, calibration</td>
<td><code>YOLOv8</code> <code>OpenCV</code> <code>RealSense D455</code></td>
</tr>
<tr>
<td><b>⚙️ Industrial Automation</b></td>
<td>Ladder logic, protocol bridging, SCADA telemetry</td>
<td><code>Delta DVP14SS</code> <code>Siemens S7</code> <code>Modbus RTU/TCP</code></td>
</tr>
<tr>
<td><b>🔌 Embedded / Edge AI</b></td>
<td>Firmware, real-time control loops, model optimization</td>
<td><code>ESP32</code> <code>Raspberry Pi</code> <code>ONNX</code> <code>TensorRT</code></td>
</tr>
<tr>
<td><b>📐 CAD & Mechanical</b></td>
<td>Enclosure design, robotic cell layout, sheet-metal fabrication</td>
<td><code>SolidWorks</code> <code>Fusion 360</code> <code>AutoCAD</code></td>
</tr>
<tr>
<td><b>🖥️ Industrial HMI</b></td>
<td>Live telemetry dashboards for production-floor monitoring</td>
<td><code>Flask</code> <code>WebSockets</code> <code>SSE</code></td>
</tr>
</table>

</div>

---

## 🚀 Flagship Deployments

<details open>
<summary><b>🍾 BottleGuardPro — AI Defect Inspection System</b> &nbsp; <img src="https://img.shields.io/badge/STATUS-LIVE_ON_LINE-3DDC97?style=flat-square&labelColor=1E1E1E"/></summary>
<br/>

> Vision-guided quality inspection running live on a Bisleri bottling conveyor — full closed loop from camera to pneumatic reject.

```mermaid
flowchart LR
    A["📷 Dual 4K Cameras"] -->|MJPEG| B["🧠 YOLOv8 Inference"]
    B -->|Defect Flag| C["🐍 Python Controller"]
    C -->|Modbus RTU| D["🔌 Delta DVP PLC"]
    D -->|Digital Out| E["⚡ Pneumatic Reject"]
    C -->|WebSocket / SSE| F["📊 Live HMI"]

    style A fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style B fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style C fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style D fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style E fill:#FFB020,stroke:#0A0E14,color:#0A0E14
    style F fill:#1E1E1E,stroke:#3DDC97,color:#E6E6E6
```

| Spec | Detail |
|---|---|
| Vision | Dual EMEET 4K, LAB-calibrated LED chamber |
| Inference | Custom YOLOv8 · 50+ defect classes · <12 ms/frame |
| Control | Delta DVP14SS via RS-232 Modbus RTU |
| HMI | Live SPC charts, false-positive retrain loop |

`Python` `OpenCV` `YOLOv8` `Flask` `PyQt5` `Delta PLC` `Modbus RTU`

<a href="https://github.com/ombhagwat18/Bottle_Defect_Detection_System"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ombhagwat18&repo=Bottle_Defect_Detection_System&theme=dark&bg_color=0A0E14&title_color=FFB020&icon_color=FFB020&text_color=E6E6E6&hide_border=true" /></a>

</details>

<details open>
<summary><b>🤖 Vision-Guided Pick & Place — Yaskawa GP12</b> &nbsp; <img src="https://img.shields.io/badge/Armstrong_Dematic-INTERNSHIP-FFB020?style=flat-square&labelColor=1E1E1E"/></summary>
<br/>

> Autonomous 6-DOF pick-and-place cell fusing depth perception with industrial motion control.

```mermaid
flowchart TD
    A["📷 RealSense D455"] -->|Depth + RGB| B["🧭 ArUco Pose Estimation"]
    B --> C["🧠 YOLOv8 Target Detector"]
    C -->|Target Pose| D["🦾 ROS 2 + MoveIt2"]
    D -->|MotoROS2| E["⚙️ YRC1000 Controller"]
    E --> F["🤖 Yaskawa GP12 Arm"]

    style A fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style B fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style C fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style D fill:#1E1E1E,stroke:#FFB020,color:#E6E6E6
    style E fill:#1E1E1E,stroke:#3DDC97,color:#E6E6E6
    style F fill:#FFB020,stroke:#0A0E14,color:#0A0E14
```

| Spec | Detail |
|---|---|
| Arm | Yaskawa Motoman GP12 · 12 kg payload · YRC1000 |
| Perception | RealSense D455 depth + ArUco pose extraction |
| Planning | ROS 2 Humble + MoveIt2, custom URDF/SRDF & DH tuning |
| Sim | Gazebo physics + RViz2 trajectory visualization |

`ROS 2 Humble` `MoveIt2` `MotoROS2` `RealSense D455` `OpenCV` `C++`

</details>

<details>
<summary><b>🛣️ Autoscanx — AI Pothole & Canal Inspection Vehicle</b> &nbsp; <img src="https://img.shields.io/badge/STATUS-FIELD_TESTED-3DDC97?style=flat-square&labelColor=1E1E1E"/></summary>
<br/>

- ESP32 telemetry streamed live to a PyQt5 desktop GUI
- Real-time canvas, map overlays, anomaly logging, remote override
- CV pipeline classifying surface flaws and depth irregularities

`ESP32` `PyQt5` `OpenCV` `Python`

</details>

<details>
<summary><b>🌱 Autonomous Weed Detection Robot</b> &nbsp; <img src="https://img.shields.io/badge/DOMAIN-AGRI_TECH-FFB020?style=flat-square&labelColor=1E1E1E"/></summary>
<br/>

- PiCamera2 real-time weed boundary segmentation
- Dual L298N drive + relay-actuated cutter and spray solenoid
- Flask portal with live stream + GPIO control panel

`Raspberry Pi 4` `Python` `OpenCV` `Flask`

</details>

<details>
<summary><b>🐾 Smart Feeding & Daycare Automation</b> &nbsp; <img src="https://img.shields.io/badge/DOMAIN-IoT-FFB020?style=flat-square&labelColor=1E1E1E"/></summary>
<br/>

- Flask server driving precision PWM servo dispensers
- Live device status via Server-Sent Events, no page refresh

`Raspberry Pi Zero W` `Flask` `SSE`

</details>

<br/>

<div align="center">

<a href="https://github.com/ombhagwat18/VisionArch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ombhagwat18&repo=VisionArch&theme=dark&bg_color=0A0E14&title_color=FFB020&icon_color=FFB020&text_color=E6E6E6&hide_border=true"/></a>
<a href="https://github.com/ombhagwat18/Camsnap"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ombhagwat18&repo=Camsnap&theme=dark&bg_color=0A0E14&title_color=FFB020&icon_color=FFB020&text_color=E6E6E6&hide_border=true"/></a>
<a href="https://github.com/ombhagwat18/OEE_software-"><img src="https://github-readme-stats.vercel.app/api/pin/?username=ombhagwat18&repo=OEE_software-&theme=dark&bg_color=0A0E14&title_color=FFB020&icon_color=FFB020&text_color=E6E6E6&hide_border=true"/></a>

</div>

---

## 🛠️ Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,js,html,css,bash,ros,arduino,raspberrypi,git,github,linux,docker,vscode&theme=dark&perline=8"/>
</p>

<div align="center">

<img src="https://img.shields.io/badge/ROS_2_Humble-22314E?style=for-the-badge&logo=ros&logoColor=white"/>
<img src="https://img.shields.io/badge/MoveIt2-FFB020?style=for-the-badge&logoColor=black"/>
<img src="https://img.shields.io/badge/Gazebo-FF6B00?style=for-the-badge&logo=gazebo&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=yolo&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/Modbus_RTU/TCP-3DDC97?style=for-the-badge&logoColor=black"/>
<img src="https://img.shields.io/badge/Delta_PLC-FFB020?style=for-the-badge&logoColor=black"/>
<img src="https://img.shields.io/badge/Siemens_S7-009999?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/SolidWorks-D6001C?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Fusion_360-FF6900?style=for-the-badge&logo=autodesk&logoColor=white"/>

</div>

---

## 📊 Live Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ombhagwat18&show_icons=true&hide_border=true&bg_color=0A0E14&title_color=FFB020&icon_color=FFB020&text_color=E6E6E6" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ombhagwat18&layout=compact&hide_border=true&bg_color=0A0E14&title_color=FFB020&text_color=E6E6E6" height="165"/>

<br/>

<img src="https://streak-stats.demolab.com?user=ombhagwat18&hide_border=true&background=0A0E14&stroke=FFB020&ring=FFB020&fire=FFB020&currStreakLabel=FFB020&sideLabels=E6E6E6&dates=888888"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=ombhagwat18&theme=darkhub&no-frame=true&no-bg=true&row=1&column=7&margin-w=8"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ombhagwat18&bg_color=0A0E14&color=FFB020&line=FFB020&point=3DDC97&hide_border=true"/>

<!--START_SECTION:waving-snake-->
<img src="https://raw.githubusercontent.com/ombhagwat18/ombhagwat18/output/github-contribution-grid-snake.svg" alt="contribution snake"/>
<!--END_SECTION:waving-snake-->

</div>

---

## 🎓 Education & Certifications

<div align="center">

| Institution / Platform | Credential | Status |
|---|---|---|
| 🎓 K.K. Wagh Institute of Engineering, Nashik | B.Tech — Robotics & Automation Engineering | 🟡 Final Year |
| 🤖 DeepLearning.AI / Coursera | Machine Learning Specialization | ✅ |
| 🧠 Google / Coursera | Generative AI Fundamentals | ✅ |
| ⚙️ Industrial Automation Institute | PLC & SCADA Programming | ✅ |
| 🤖 The Construct / Udemy | ROS & ROS 2 Development | ✅ |
| 🔌 Embedded Systems Certification | ESP32 / Arduino / Raspberry Pi | ✅ |

</div>

---

## 💼 Experience Timeline

```text
2024        Armstrong Dematic, Nashik — Automation & Robotics Intern
            └─ Vision-guided GP12 pick & place — ROS 2 · MoveIt2 · MotoROS2 · RealSense D455

2023-24     BottleGuardPro — Industrial Project Lead
            └─ YOLOv8 · Delta PLC · Modbus RTU · OpenCV · Flask HMI

2023        Codephoton — Software Developer Intern
            └─ ESP32 IoT garbage-van monitoring, web dashboard, telemetry ingestion

2022-23     Competitions & Prototypes
            └─ Roborace ESP32 autonomous chassis · Autoscanx inspection vehicle · Weed-cutting robot
```

---

## 🏅 Recognition

- 🏁 Roborace builder — custom ESP32 obstacle-avoidance rover chassis
- 🤖 Facilitated hands-on ROS/microcontroller workshops
- 🏆 Deployed end-to-end vision-to-PLC control loop live on a production line
- 🎯 Selected for Armstrong Dematic's Automation & Robotics R&D internship

---

## ❓ FAQ

<details>
<summary><b>What roles am I looking for?</b></summary><br/>
Robotics Engineering, ROS 2 development, Computer Vision / AI Engineering, and Industrial Automation roles.
</details>

<details>
<summary><b>Hardware, software, or both?</b></summary><br/>
Both — I connect full-stack software (Python, C++, ROS 2, PyTorch) to physical systems (industrial arms, PLCs, ESP32, pneumatics, depth cameras).
</details>

<details>
<summary><b>Open to collaboration?</b></summary><br/>
Yes — reach out for open-source ROS 2 packages, vision pipelines, or automation projects.
</details>

---

<div align="center">

> *"Engineering is turning 'what if?' into 'it works.'"*

<a href="mailto:ombhagwat18@gmail.com"><img src="https://img.shields.io/badge/Email-ombhagwat18%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/ombhagwat18"><img src="https://img.shields.io/badge/LinkedIn-Om_Bhagwat-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/ombhagwat18"><img src="https://img.shields.io/badge/GitHub-ombhagwat18-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:0A0E14,50:1A1206,100:0A0E14&height=120&section=footer"/>

**⭐ Star my repos if any of this is useful to you!**

</div>
