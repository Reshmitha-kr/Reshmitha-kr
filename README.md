<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Reshmitha%20K%20R&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%2FML%20Engineer%20%7C%20B.Tech%20CSE-AI%20Student&descAlignY=62&descSize=16" width="100%"/>

Kerala, India · [LinkedIn](https://www.linkedin.com/in/reshmitha-kr) · [Email](mailto:rreshmithakr@gmail.com)

</div>

---

## About

B.Tech student in Computer Science and Artificial Intelligence with hands-on project experience across machine learning, deep learning, computer vision, NLP, robotics, and IoT. Comfortable working end-to-end — from embedded sensor systems and ROS-based robots to full-stack web applications with integrated ML models. Particularly interested in applied AI for healthcare, robotics, and intelligent automation.

---

## Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=python,java,javascript,tensorflow,keras,opencv,sklearn,flask,docker,kubernetes,gcp,mongodb,git,jupyter,raspberrypi&theme=dark" />
</div>

<br>

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

**Machine Learning & Deep Learning**
<p>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
</p>

**Robotics & Embedded Systems**
<p>
  <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
</p>

**Web, Cloud & Tools**
<p>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white"/>
</p>

---

## Projects

<div align="center">

| Project | Category | Stack | Highlights |
|---|---|---|---|
| **Early Prediction of Pancreatic Cancer Using Deep Learning** | <img src="https://img.shields.io/badge/-Deep%20Learning-70A5FD?style=flat-square"/> | Python, TensorFlow, Keras, ResNet50, ViT, Grad-CAM | Compared ResNet50 and Vision Transformer on 23,000+ CT images for cancer classification; **86% / 81% accuracy**; Grad-CAM for interpretability |
| **Personalized Music Therapy System Using Acoustic AI** | <img src="https://img.shields.io/badge/-Audio%20AI-BF91F3?style=flat-square"/> | Python, Librosa, Scikit-learn, Spotify API | Emotion recognition from MFCC/ZCR/RMS features; Random Forest & XGBoost at **78% accuracy**; mood-based Spotify recommendations |
| **AI-Based Adaptive Traffic Signal Control** | <img src="https://img.shields.io/badge/-Reinforcement%20Learning-38BDAE?style=flat-square"/> | Python, SUMO, Multi-Agent RL, Streamlit | Multi-agent RL for adaptive traffic signals with reward shaping and emergency vehicle prioritization in SUMO |
| **AI-Powered Smart Donation & Impact Recommendation System** | <img src="https://img.shields.io/badge/-Full--Stack-F7931E?style=flat-square"/> | MERN Stack, Python, Machine Learning | Full-stack donation platform with JWT auth, role-based access, and ML-based recommendations |
| **ROS-Based Exploration Robot for Human Safety Validation** | <img src="https://img.shields.io/badge/-Robotics-22314E?style=flat-square&logo=ros&logoColor=white"/> | ROS2, Raspberry Pi, Python, YOLOv8, OpenCV, SLAM | Autonomous exploration robot with SLAM navigation and real-time YOLOv8n object/hazard detection for safety monitoring |
| **IoT-Based Smart Wheelchair** | <img src="https://img.shields.io/badge/-IoT-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/> | ESP32, HC-SR04, MPU6050, L298N | Intelligent mobility aid with obstacle/fall detection, joystick control, and real-time health monitoring over Wi-Fi |

</div>

<br>

<details>
<summary><b>ROS-Based Exploration Robot — Project Details</b></summary>
<br>

**Motivation:** Send a robot into hazardous or inaccessible areas instead of humans, providing real-time environmental data (gas levels, heat, obstacles) and safety alerts.

**System architecture**
- *Hardware:* Raspberry Pi running the ROS2 interface and motor control, with camera, IMU, and gas/temperature sensors for perception and monitoring.
- *Software:* Perception modules for object and hazard detection, SLAM-based autonomous navigation, a safety system that halts the robot and raises alerts on dangerous conditions, and localization/logging modules for tracking position and system data.

**Deep learning component:** Real-time object detection using **YOLOv8n** via the Ultralytics library, optimized for low-power hardware. The pipeline continuously captures frames via OpenCV, runs YOLOv8n inference to detect and localize objects, annotates frames with bounding boxes, and streams the result to a web interface.

**Key challenges addressed:** safe navigation in unknown/cluttered spaces, handling noisy sensor data, and maintaining real-time communication across all ROS nodes.

</details>

<details>
<summary><b>IoT-Based Smart Wheelchair — Project Details</b></summary>
<br>

**Objective:** Develop a smart wheelchair that assists users through sensor-based automation, remote monitoring, and health tracking — improving mobility, safety, and independence.

**Components:** ESP32 Wi-Fi microcontroller, ultrasonic sensor (HC-SR04) for obstacle detection, MPU6050 accelerometer, L298N motor driver with DC motors, pulse sensor for health monitoring, joystick/push-button controls, and buzzer for alerts.

**Features**
- Real-time obstacle detection with alert system
- Fall detection and emergency alerts
- Multiple control modes, including joystick navigation
- Continuous health monitoring via pulse sensor
- Real-time data transfer over Wi-Fi to a remote interface

**Impact:** Designed to empower elderly and differently-abled individuals by improving safety, enabling remote health monitoring, and reducing dependence on caregivers.

*Team project — built collaboratively as part of an IoT-based intelligent mobility systems project at Amrita Vishwa Vidyapeetham.*

</details>

---

## Research (Ongoing)

<details>
<summary><b>Android-Offloading: Cloud-Integrated Offloading System</b></summary>
<br>

> `Android` `Flask` `Google Cloud`

- Developing a cloud-integrated computation offloading framework to improve device performance and energy efficiency.
- Built a Flask-based backend for handling remote computation and task execution.
- Implementing battery-aware task migration strategies based on device conditions.
- Integrating Google Cloud services for remote processing and real-time device-server communication.

</details>

---

## Professional Simulations (Forage)

| Program | Organization | Completed |
|---|---|---|
| Software Engineering | Skyscanner | June 2026 |
| Software Engineering | JPMorgan Chase & Co. | June 2026 |
| Advanced Software Engineering | Walmart Global Tech | January 2026 |
| Red Bull Role Match Quiz | Red Bull | July 2025 |
| Technology | Deloitte Australia | February 2025 |

---

## Achievements & Certifications

| Category | Achievement | Details |
|---|---|---|
| Certification | AI Fundamentals | IBM, 2025 |
| Certification | Cisco Certified Support Technician — Cybersecurity | Cisco, 2024 |
| Certification | Microsoft Azure Courses | Microsoft, 2024 |
| Community Initiative | AI Awareness for Farmers (SSR Initiative) | Conducted sessions on AI applications & data-driven farming, 2025 |
| Community Service | Amrita Seva Program — VCC Coordinator | Led community service & social welfare initiatives, 2023-2025 |

---

## Education

| Degree | Institution | Year | Score |
|---|---|---|---|
| B.Tech, Computer Science & Artificial Intelligence | Amrita Vishwa Vidyapeetham, Amritapuri | 2023 - 2027 | CGPA: 7.15 |
| 12th Grade (Kerala State Board) | Vijayamatha Convent School, Palakkad | 2022 - 2023 | 83% |
| 10th Grade (Kerala State Board) | Vijayamatha Convent School, Palakkad | 2020 - 2021 | 98.2% |

---

## Currently Learning

```text
Reinforcement Learning   - Multi-Agent Systems, Reward Shaping
NLP & LLMs                - Transformers, Hugging Face, Prompting Techniques
Cloud & DevOps            - Kubernetes, Google Cloud, CI/CD
```

---
## GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=Reshmitha-kr&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"/>

<img height="165em" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=Reshmitha-kr&layout=compact&theme=tokyonight&hide_border=true"/>

</div>

---

## Connect

<p>
  <a href="https://www.linkedin.com/in/reshmitha-kr">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=rreshmithakr@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>
