<div align="center">

# Harishwaran T

### Robotics Software Engineer — Perception · Navigation · Manipulation

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=4A9EFF&center=true&vCenter=true&width=800&lines=Robotics+Intern+%40+Spotless+AI+Robotics;Deploying+Hospital+Disinfection+Robots+on+ROS2;SLAM+%7C+Nav2+%7C+MoveIt+%7C+YOLO+%7C+Computer+Vision)

[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Harishwaran25)
[![Gmail](https://img.shields.io/badge/GMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harishwaranxia@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)

![Profile Views](https://komarev.com/ghpvc/?username=Harishwaran25&color=blue&style=for-the-badge)
![Open to Work](https://img.shields.io/badge/OPEN%20TO%20WORK-brightgreen?style=for-the-badge)

</div>

---

### About Me

```python
class Harishwaran:
    role       = "Robotics Intern @ Spotless AI Robotics"
    education  = "B.E. Robotics and Automation, SREC (2023–2027)"
    location   = "Tamil Nadu, India"

    focus = [
        "Autonomous Mobile Robots (SLAM, Nav2, AMCL)",
        "Robotic Manipulation (MoveIt 2, TF2)",
        "Computer Vision & Detection (YOLOv5/v8/v11, OpenCV)",
        "Embedded Systems & Edge Deployment (Raspberry Pi, Arduino)",
    ]

    currently_building = "Autonomous UV disinfection robots deployed on live hospital sites"
```

---

### 🛠️ Tech Stack

*(hover over an icon — click to visit its docs)*

<div align="center">

**Perception**
<br>
<a href="https://opencv.org/" target="_blank"><img src="https://skillicons.dev/icons?i=opencv" /></a>
<a href="https://www.tensorflow.org/" target="_blank"><img src="https://skillicons.dev/icons?i=tensorflow" /></a>
<a href="https://pytorch.org/" target="_blank"><img src="https://skillicons.dev/icons?i=pytorch" /></a>
<a href="https://scikit-learn.org/" target="_blank"><img src="https://skillicons.dev/icons?i=sklearn" /></a>
<img src="https://cdn.simpleicons.org/googlemediapipe/0097A7" width="48" height="48" alt="MediaPipe" style="vertical-align:middle; margin:0 4px;"/>
<img src="https://cdn.simpleicons.org/huggingface/FFD21E" width="48" height="48" alt="Hugging Face" style="vertical-align:middle; margin:0 4px;"/>
![YOLO](https://img.shields.io/badge/YOLO-v5%2Fv8%2Fv11-111111?style=for-the-badge)

<br><br>

**Navigation, SLAM & Manipulation**
<br>
<a href="https://www.ros.org/" target="_blank"><img src="https://skillicons.dev/icons?i=ros" /></a>
![Nav2](https://img.shields.io/badge/Nav2-11151C?style=for-the-badge)
![AMCL](https://img.shields.io/badge/AMCL-11151C?style=for-the-badge)
![SLAM_Toolbox](https://img.shields.io/badge/SLAM_Toolbox-11151C?style=for-the-badge)
![MoveIt2](https://img.shields.io/badge/MoveIt_2-11151C?style=for-the-badge)
![TF2](https://img.shields.io/badge/TF2-11151C?style=for-the-badge)
![RViz](https://img.shields.io/badge/RViz-11151C?style=for-the-badge)

<br><br>

**Simulation & CAD**
<br>
<a href="https://gazebosim.org/" target="_blank"><img src="https://skillicons.dev/icons?i=gazebo" /></a>
<img src="https://cdn.simpleicons.org/autodesk/FF6600" width="48" height="48" alt="Fusion 360" style="vertical-align:middle; margin:0 4px;"/>
<img src="https://cdn.simpleicons.org/dassaultsystemes/E4292F" width="48" height="48" alt="SolidWorks" style="vertical-align:middle; margin:0 4px;"/>

<br><br>

**Embedded & Hardware**
<br>
<a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=raspberrypi,arduino" /></a>

<br><br>

**Data & Analysis**
<br>
<a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=python" /></a>
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

<br><br>

**Core Programming & Systems**
<br>
<a href="#" target="_blank"><img src="https://skillicons.dev/icons?i=python,c,git,github,linux,vscode" /></a>
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

</div>

---

### 🤖 Projects

*(click a project to expand)*

<details>
<summary><b>MediSense</b> — Contactless Patient Safety Monitoring System</summary>
<br>

Real-time CV system monitoring bedridden patients for falls, agitation, unconsciousness, and posture changes across 6 modules.

- MediaPipe pose tracking integrated with YOLO for real-time scene detection
- Rolling-window smoothing + 3-stage confirmation state machine cut false alarms by **27%**
- Non-blocking Hugging Face emotion-detection thread — zero added latency
- Refactored into a production-style package with a full **pytest** suite

`Python` `OpenCV` `YOLO` `MediaPipe` `Hugging Face` `pytest`
</details>

<details>
<summary><b>UVDS Autonomous Navigation Robot</b> — Spotless AI Robotics</summary>
<br>

AI-powered ROS2 robot for non-touch UV-C hospital disinfection, deployed across 4 live hospital sites.

- Configured and tuned a SLAM Toolbox mapping/localization pipeline for on-site navigation
- Validated navigation in RViz ahead of live runs, supporting hidden-area detection and full-coverage routing
- Diagnosed and resolved mapping drift and Nav2-stack issues during real-world commissioning

`ROS2` `SLAM Toolbox` `Nav2` `RViz` `Linux`
</details>

<details>
<summary><b>Swarm Robotics using ROS2</b></summary>
<br>

2-robot swarm system focused on inter-robot communication, coordination, and scalability.

- ROS2 nodes, topics, and services for distributed control and real-time data exchange
- Formation control, task allocation, and cooperative navigation behaviors
- ~90% successful task completion across simulation runs

`ROS2` `Python`
</details>

<details>
<summary><b>Crime Detection using YOLO</b> — Real-time Surveillance</summary>
<br>

Python-based AI surveillance system for real-time detection of weapons, suspicious objects, and unusual activity.

- YOLOv5 + OpenCV + TensorFlow pipeline on a custom-labelled dataset
- Lightweight edge-inference version deployed on Raspberry Pi
- 90%+ accuracy detecting potential threats in controlled tests

`Python` `YOLOv5` `OpenCV` `TensorFlow` `Raspberry Pi`
</details>

<details>
<summary><b>Multipurpose Agri-Bot</b></summary>
<br>

Modular autonomous agricultural robot for ploughing, irrigation, and spraying operations.

- Designed and fabricated in Fusion 360
- IoT-based remote controls, plough attachment, water tank/pump for irrigation
- Arduino-based control system for multi-task farming operations
- Reduced manual labour by **60%** in prototype field testing

`Fusion 360` `Arduino` `IoT`
</details>

---

### 💼 Work Experience

<details>
<summary><b>Robotics Intern — Spotless AI Robotics</b> · Jan 2026 – Present</summary>
<br>

- Deployed and validated ROS2-based autonomous UV disinfection robots across 4 hospital/facility sites
- Tuned SLAM Toolbox mapping and localization pipelines, reducing mapping drift by **~15%**
- Diagnosed and resolved recurring Nav2 planner failures across 6+ field trials, improving routing reliability by **~20%**
- Validated full-coverage disinfection routing across **~2,000 sq. ft** per session
</details>

<details>
<summary><b>IoT Intern — Apex I Sys</b> · Jun 2025</summary>
<br>

- Built and deployed a real-time Raspberry Pi surveillance system, **~85%** detection accuracy, sub-5s alerting
- Programmed event-detection logic in Python across 2 notification channels
</details>

<details>
<summary><b>CAD Designer — Karthikesh Robotics Pvt Ltd</b> · Jan – Feb 2025</summary>
<br>

- Designed and modelled 10+ mechanical components/assemblies in Fusion 360 and SolidWorks
- Reduced material usage by **~12%** across assemblies
- Cut prototype iteration time by 2 days/cycle across 3 projects
</details>

---

### 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Harishwaran25&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Harishwaran25&layout=compact&theme=tokyonight&hide_border=true" height="165"/>

<img src="https://streak-stats.demolab.com/?user=Harishwaran25&theme=tokyonight&hide_border=true" height="165"/>

</div>

<details>
<summary>📈 Contribution Activity Graph (click to expand)</summary>
<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Harishwaran25&theme=tokyo-night&hide_border=true" width="100%"/>

</details>

---

### 🎓 Education

**B.E. Robotics and Automation** — Sri Ramakrishna Engineering College (2023–2027)
CGPA: 8.79 / 10

---

### 📜 Certifications

<details>
<summary>Click to expand</summary>
<br>

- Control System Basics — e-Yantra, IIT Bombay
- MicroROS Basics — e-Yantra, IIT Bombay
- Artificial Intelligence with Python — E-Cell, IIT Madras

</details>

---

<div align="center">
📫 Reach me at <b>harishwaranxia@gmail.com</b>
</div>
