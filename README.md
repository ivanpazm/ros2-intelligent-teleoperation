# ROS2 Intelligent Teleoperation Platform (Local AI + MCP Tools + Web Operator UI)

This repository contains the foundations of an intelligent teleoperation platform for mobile robots built on **ROS2**, featuring a **web‑based operator interface**, **local AI using Ollama**, **custom MCP tools**, and a **lightweight Android vision app**.

The entire system runs **100% locally**, with no cloud services, no external APIs, and no vendor lock‑in.

![ROS2](https://img.shields.io/badge/ROS2-Humble-blue)
![Ollama](https://img.shields.io/badge/AI-Ollama-green)
![MCP](https://img.shields.io/badge/MCP-Custom-orange)
![Android](https://img.shields.io/badge/Android-Vision_App-brightgreen)
![WebUI](https://img.shields.io/badge/Web-Operator_UI-lightgrey)


---

## 🎥 Demo Video

**Local LLM (Ollama) running custom MCP tools for image recognition inside the Operator UI:**

👉 https://youtu.be/cizPrbYwczA

---

## 🚀 Key Features

- **Web Operator UI**  
  Real‑time control, state visualization, and operator tools.

- **Local AI (Ollama)**  
  The LLM runs fully on‑device with minimal hardware requirements.  
  No cloud, no APIs, no recurring costs.

- **Custom MCP Tools**  
  Purpose‑built tools for:  
  - Frame capture  
  - Image analysis  
  - Scene description  
  - Operator assistance  

- **Android Vision App**  
  Lightweight app that turns any Android phone into the robot’s camera via MJPEG streaming.

- **ROS2 Backend**  
  Movement, state access, diagnostics, and robot services.

- **Sensor Fusion (EKF)**  
  IMU + odometry fusion for stable, filtered pose estimation.

- **Modular Architecture**  
  Clean Node/TypeScript bridge between ROS2 and the web UI.

---

## 📱 Android Vision App

The platform includes a **lightweight Android application** that transforms any smartphone into a real‑time vision sensor for the robot.  
The app streams **MJPEG video** directly to the Operator UI and to the MCP tools used by the local LLM.

### Main Features
- Stable, low‑latency MJPEG streaming  
- Minimal configuration (open and stream)  
- Works on any modern Android device  
- No special permissions or external libraries  
- Direct integration with MCP vision tools  
- Operates over local WiFi (no cloud required)

### Benefits
- Real‑time vision without dedicated hardware  
- Lower hardware cost  
- Fast prototyping in any environment  
- Perfect integration with local AI (Ollama)  
- Ideal for mobile robots, inspection, and teleoperation

---

## 🧩 Architecture Overview

- **ROS2 Nodes** — control, state, sensors, EKF  
- **Web Operator UI** — control panel, video, AI tools  
- **MCP Tools** — LLM‑accessible extensions  
- **Ollama LLM** — local language + vision processing  
- **Android Vision App** — MJPEG streaming camera  

---

## 💻 Requirements

- Standard gaming PC  
- Ollama installed  
- ROS2 (Humble/Foxy compatible)  
- Node.js + TypeScript  
- Android phone for vision  
- Modern web browser  

No professional GPU or cloud services required.

---

## 📌 Project Status

The system is **functional** and under active development.  
Currently implemented:

- Basic teleoperation  
- Operator UI  
- Vision streaming  
- Stable EKF  
- Local LLM integration  
- MCP tools for vision  
- Android camera app  

Next steps:

- Full integration with real mobile robots  
- Additional MCP tools  
- UI improvements  
- Extended documentation  

---

## 🤝 Looking for Collaborators

I’m looking for a technical collaborator (ROS2, robotics, AI, integrators) interested in taking this platform to the next level.

If you want to collaborate, integrate this into your robots, or see the full demo:

📩 **Contact me via GitHub or LinkedIn.**

---

## 📄 License

To be defined.
