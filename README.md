<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0a2a1a,100:0d1117&height=200&section=header&text=Milind%20Late&fontSize=62&fontColor=3fb950&animation=fadeIn&fontAlignY=40&desc=Physical%20AI%20Engineer%20%E2%80%94%20Robotics%20%E2%80%94%20Edge%20Inference%20%E2%80%94%20Computer%20Vision&descAlignY=63&descColor=7ee787&descSize=15" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=2600&pause=1000&color=3FB950&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=60&lines=AIR+4+%E2%80%94+ISRO+IRoC-U+2025+%7C+1%2C600%2B+competing+teams;ROS2+%7C+YOLOv8+%7C+NVIDIA+Jetson+%7C+OAK-D+Pro+%7C+Sensor+Fusion)](https://github.com/MilindLate)

<br/>

[![ISRO](https://img.shields.io/badge/ISRO%20IRoC--U%202025-AIR%204%20%7C%201%2C600%2B%20Teams-FF6B35?style=for-the-badge)](https://github.com/MilindLate)
[![SIH](https://img.shields.io/badge/SIH%202025-Finalist%20%7C%20Top%205%20of%20500%2B-FF6B35?style=for-the-badge)](https://github.com/MilindLate)
[![Google](https://img.shields.io/badge/Google%20Student%20Ambassador-GID%205926-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://me.developers.google.com/u/milindlate)
[![Papers](https://img.shields.io/badge/Publications-3%20%7C%20IEEE%20%26%20Springer-00B37E?style=for-the-badge&logo=researchgate&logoColor=white)](https://scholar.google.com/citations?user=5c9MuwEAAAAJ)
[![Views](https://komarev.com/ghpvc/?username=MilindLate&color=3fb950&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/MilindLate)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-myp--7c9t.vercel.app-0d1117?style=for-the-badge&logo=vercel&logoColor=white)](https://myp-7c9t.vercel.app/)
[![Scholar](https://img.shields.io/badge/Google%20Scholar-3%20Papers-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=5c9MuwEAAAAJ)
[![GDG](https://img.shields.io/badge/Google%20Developer-GID%205926-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://me.developers.google.com/u/milindlate)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-milind--late-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/milind-late)
[![Email](https://img.shields.io/badge/Email-milindlate9%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:milindlate9@gmail.com)

</div>

<br/>

---

## Who I am

B.Tech CSE (AI/ML) student at YCCE Nagpur, graduating June 2027. I build autonomous systems that run on real hardware — drones, robotic arms, embedded platforms. My work spans edge AI inference, sensor fusion, computer vision, and time-series ML, validated at national competitions including ISRO, IIT Bombay, and Smart India Hackathon.

> **Philosophy:** Deploy ML on real hardware. Not just notebooks.

<br/>

---

## Highlights

| | Achievement | Scale |
|:---:|:---|:---|
| 🥇 | **ISRO IRoC-U 2025 — AIR 4** | 1,600+ competing teams · Team Titans 2025 |
| 🏅 | **SIH 2025 Finalist** | Top 5 of 500+ entries · Ministry of Power · Problem ID 25193 |
| 🤖 | **e-Yantra IIT Bombay** | 95%+ task success rate · Autonomous UR5 arm + UGV |
| 🎓 | **Google Student Ambassador** | GID 5926 · 200+ students engaged |
| 📄 | **3 Peer-Reviewed Publications** | IEEE + Springer Nature · 2024 |
| 🌍 | **NASA Space Apps Challenge** | WeatherEye — real-time emergency weather & fire prediction |

<br/>

---

## Featured projects

---

### Autonomous UAV — ISRO IRoC-U 2025 &nbsp; `AIR 4 / 1,600+ Teams`

> End-to-end autonomous aerial platform built at Electus Technologies Pvt. Ltd. — real-time object detection, stereo depth-based landing zone identification, and production-grade edge AI on NVIDIA Jetson Nano.

**Key outcomes**
- Sub-10ms sensor fusion latency via deterministic serial bridge: Cube Orange ↔ Jetson ↔ ESP32
- YOLOv8 running at production frame rates on memory-constrained Jetson Nano VRAM
- 3D obstacle mapping and safe landing zone validation using OAK-D Pro stereo AI
- Ranked 4th nationally among 1,600+ teams by ISRO

```
PERCEPTION          DECISION ENGINE         ACTUATION
──────────────────────────────────────────────────────
OAK-D Pro        →  NVIDIA Jetson Nano   →  Cube Orange FC
├─ RGB Feed          ├─ ROS2 Node Mesh       ├─ MAVLink Protocol
├─ Depth Map         ├─ YOLOv8 Inference     ├─ Motor PWM + ESC
└─ Stereo AI         ├─ Path Planner         └─ Fail-Safe Logic
                     └─ Obstacle Avoidance
ESP32 MCU           Custom Pub/Sub           ESP32 MCU
└─ Telemetry         ROS2 DDS Transport      └─ Servo + Relay
```

`ROS2` `YOLOv8` `OpenCV` `NVIDIA Jetson Nano` `OAK-D Pro` `Cube Orange` `ESP32` `MAVLink` `Python` `C++`

[![View Repo](https://img.shields.io/badge/View%20Repository-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MilindLate/Real-Time-Safe-landing-zone-Detection-Model-for-UAVs-ANAVs-Using-Depth-camera-)

---

### Supply Chain Intelligence — Smart India Hackathon 2025 &nbsp; `Finalist · Top 5 of 500+`

> LSTM-based time-series forecasting system for India's Ministry of Power — national-scale government procurement optimization. Problem ID 25193.

**Key outcomes**
- Multi-step ahead forecasting of material procurement volumes across supply chain nodes
- Anomaly detection pipeline integrated into the TensorFlow training and inference stack
- Selected as top 5 of 500+ SIH entries by Ministry of Power evaluators

`Python` `TensorFlow` `LSTM` `Time-Series ML` `Deep Learning` `Data Analysis`

[![View Repo](https://img.shields.io/badge/View%20Repository-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MilindLate)

---

### KrishiCobot — e-Yantra IIT Bombay &nbsp; `Top Performer · 95%+ Task Success Rate`

> Autonomous precision agriculture system — UR5 robotic arm + UGV with Intel RealSense D435 for crop inspection and field operations, validated in Linux-based ROS2 Gazebo simulation.

**Key outcomes**
- Full autonomous manipulation pipeline: pick, place, and precision reach across field coordinates
- 95%+ task success rate across multi-environment Gazebo simulation scenes
- 3D spatial reasoning via RealSense D435 depth camera for crop detection and obstacle identification

`ROS2` `UR5 Robotic Arm` `Intel RealSense D435` `Python` `C++` `Linux` `Gazebo`

[![View Repo](https://img.shields.io/badge/View%20Repository-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MilindLate/eyrc-25-26-krishi-cobot)

---

### MarineGuide — Google Solution Challenge 2026

> Smart maritime supply chain platform — BigQuery analytics, deep learning demand forecasting, and Google Cloud AI for real-time route optimization. Cross-platform mobile app in Flutter + Firebase.

`Flutter` `Firebase` `BigQuery` `Google Cloud AI/ML` `Deep Learning` `REST APIs`

[![View Repo](https://img.shields.io/badge/View%20Repository-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MilindLate)

---

### WeatherEye — NASA Space Apps Challenge

> Real-time emergency weather prediction and forest fire risk mapping using NASA Earth Observation geospatial APIs, with automated GitHub Actions CI/CD deployment.

`TypeScript` `NASA Earth APIs` `CI/CD` `GitHub Actions` `Geospatial ML`

[![View Repo](https://img.shields.io/badge/View%20Repository-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MilindLate/WeatherEye)

---

<br/>

## Technical skills

### AI / ML / Deep Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-FF4500?style=flat-square)
![LSTM](https://img.shields.io/badge/LSTM-Time--Series-8B5CF6?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-00B37E?style=flat-square)
![LLM Fine-tuning](https://img.shields.io/badge/LLM%20Fine--tuning-58a6ff?style=flat-square)

### Robotics / Embedded / Hardware
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OAK-D Pro](https://img.shields.io/badge/OAK--D%20Pro-9C27B0?style=flat-square)
![Cube Orange](https://img.shields.io/badge/Cube%20Orange%20FC-FF6B35?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

`Sensor Fusion` · `MAVLink` · `UAV / UGV Architectures` · `Fail-Safe Systems` · `UR5 Robotic Arm`

### Languages
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### Cloud / Web / Data
![React](https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

---

## Publications

| Venue | Title | Year |
|---|---|---|
| **IEEE** | Development of Sustainable E-Book Portal | 2024 |
| **Springer Nature** · RCAAI 2024 · MIT Manipal × MNIT Jaipur | Artificial Intelligence Supporting Gender Equality | 2024 |
| **Springer** · ICT4SD 2024 · Goa | Web-Based Sustainable Waste Minimization System | 2024 |

→ [Google Scholar profile](https://scholar.google.com/citations?user=5c9MuwEAAAAJ)

<br/>

---

## Leadership

| Role | Organization | Period |
|---|---|---|
| **Event Organization Head & Core Member** | YCCE Media + ISTE | 2023–Present |
| **Mentor & Guest Lecturer** | Robotics & AI/ML · SIH, e-Yantra, National Competitions | 2024–Present |
| **Google Student Ambassador** | GID 5926 · 200+ students engaged | 2026–Present |
| **Publicity Head** | Young India Network (Sakal Media) | 2023–2025 |

<br/>

---

## GitHub analytics

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=MilindLate&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=3fb950&icon_color=3fb950&text_color=8b949e&border_radius=10"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MilindLate&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=3fb950&text_color=8b949e&border_radius=10"/>

<br/>

[![Streak](https://streak-stats.demolab.com?user=MilindLate&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=3fb950&ring=3fb950&fire=FF6B35&currStreakLabel=3fb950&border_radius=10)](https://git.io/streak-stats)

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a2a1a,100:0d1117&height=120&section=footer&text=Building%20machines%20that%20see%2C%20decide%2C%20and%20act%20%E2%80%94%20at%20the%20edge%2C%20in%20real%20time.&fontSize=13&fontColor=7ee787&animation=fadeIn" width="100%"/>

</div>
