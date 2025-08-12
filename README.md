# AI & Systems Portfolio — Mohamed Elshamy

Curated highlights across **AI Agents, Hardware Security for SoCs, Computer Vision, IoT/Embedded**, and **TinyML**. Each item links to code, papers, or demos.

---
## End-to-End Projects

### 🤖 Meeting Scheduler AI Agent (Telegram, Text + Voice)
Agent that parses requests, asks for missing details, optionally checks owner’s calendar, confirms, creates the event, and emails the employee with the invite link.  
**Stack:** n8n, Telegram Bot API, Google Calendar, Gmail API, RAG prompts  
**Impact:** Reduces manual scheduling + miscommunication for small teams.  
**Links:** Code (repo), Demo (video)

### 🔥 Cluster-BPI — Fine-Grain Blind Power Identification for Multicores
Defends against **hardware thermal Trojans** by improving BPI via DBSCAN-aided NMF initialization; **~77% error reduction** in simulations.  
**Paper:** IEEE IPCCC 2024  
**Links:** Paper, Code (repo), Slides

### 🧠 CPINN-ABPI — Physics-Informed Power Estimation in MPSoCs
First hardware validation of ABPI on **Jetson Xavier AGX**; introduces a **physics-informed** hybrid with NSGA-II tuning. **MAE ↓ 84.7% (CPU), 73.9% (GPU)** with sub-ms inference.  
**Paper:** arXiv 2025  
**Links:** https://arxiv.org/abs/2505.22469 · Code (repo)

### 🚗 p-YOLOv8 Distracted Driving (Real-Time)
Efficient, accurate driver distraction detection for embedded deployment.  
**Paper:** IEEE HPEC 2024  
**Links:** https://arxiv.org/abs/2410.15602 · Code (repo)

### 📡 Telematics Devices (2- & 4-Layer) + Industrial IoT
Vehicle tracking (fleet), smart impounding, RS485/RS232/GPRS/Wi-Fi data logger; wide-range power (9–30V), rich I/O, backup power & charger.  
**Links:** Design notes (repo), Demo (video)

### 🎯 Ball-on-Plate Control (Hybrid PD/ML + Fuzzy)
Hybrid pseudo-PD/ML with fuzzy online tuning; servo angle prediction ~99.9% across models; validated in sim & hardware.  
**Paper:** J. Phys.: Conf. Ser. 2021  
**Links:** Paper · Code (repo)

---
## Skill-Based Projects

### Agents & RAG
- **Voice-enabled Telegram Agent** for internal workflows (scheduling, summaries, Q&A)
- **Document QA over Google Drive** using embeddings + function calling

### Hardware Security & SoC Analytics
- **Thermal Trojan studies** (error/robustness analyses, BIC/ABPI variants)
- **Fine-grained power ID** from steady-state temps; clustering + NMF pipelines

### Computer Vision
- **Real-time driver monitoring** (YOLOv8 compression & latency tuning)
- **Axis/Hikvision AI camera programming** for monitoring systems

### TinyML & Edge
- **On-device inference** on ESP32/STM32 & Jetson; pipeline for quantization/pruning

### Data Engineering / MLOps
- **FastAPI inference services**, experiment tracking, and deployment checklists

---
## Publications (selected)

- **CPINN-ABPI** — arXiv 2025. https://arxiv.org/abs/2505.22469  
- **MATTER: Multi-stage Adaptive Thermal Trojan** — ISQED 2025.  
- **p-YOLOv8: Distracted Driving** — IEEE HPEC 2024.  
- **Cluster-BPI** — IEEE IPCCC 2024.  
- **Fine-Grained Clustering-Based Power ID** — IEEE IGSC 2024.  
- **Brain Tumor Detection (DL)** — CPE 2022.  
- **Ball-on-Plate Hybrid PD/ML** — J. Phys.: Conf. Ser. 2021.

> Full list: Google Scholar (see profile README)

---
## Skills

**AI/ML:** PyTorch, TensorFlow, scikit-learn, YOLO, CV, NLP, RAG/Agents  
**Edge/Embedded:** ESP32, STM32, FPGA, Jetson Xavier AGX  
**HW/EDA:** KiCad, Altium, PCB (2–4-layer+), FCC/UL compliance  
**Modeling/Control:** MATLAB/Simulink, signal processing, thermal/power models  
**Systems:** FastAPI, Linux, Docker, n8n, Git  
**Langs:** Python, C/C++, Verilog/VHDL

---
## Awards
- Scientific Excellence Award — Menoufia University
- 2× Awards, International Intelligent Robot Contest (Morocco)
- Certificates of Excellence — Egyptian Army Technical Research Center

---
## Education
- **PhD, Electrical & Computer Engineering — NMSU** (GPA 4.0)  
- **M.Sc., Control & Industrial Power Electronics (ML)** — Menoufia (GPA 4.0)  
- **B.Sc., Electrical & Electronic Engineering** — Menoufia (GPA 3.81)

---
## Contact
**Email:** elshamy@nmsu.edu · **LinkedIn:** /in/moh-elshamy/ · **YouTube:** @mohamedelshamy4694

---

### How this repo is organized
- **End-to-End Projects:** problem → approach → results → links  
- **Skill-Based:** targeted techniques & components  
- **Publications:** selected peer-reviewed work  
- **Skills / Awards / Education:** quick reference

> Tip: Pin this repo + your top 5 project repos on your profile.
