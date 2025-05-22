# Context-Aware SIID Detection & Elderly Monitoring System

This project presents a unified AI system for detecting **Situationally Induced Impairments (SIIDs)** — temporary communication limitations due to real-world contexts like multitasking, dim lighting, or hand engagement.

🔍 It also includes an **elderly safety prototype** for monitoring fall risks and posture-based hazards.

## 🔧 Key Features
- **YOLOv8** – Object detection
- **BLIP-2** – Scene & activity captioning
- **MediaPipe** – Hand/posture detection
- **Brightness Estimation** – Vision quality
- **Mistral-7B (LLM)** – Reasoning via structured prompts
- Predicts channel availability: **Vision | Vocal | Hand**

## 🧠 Architecture

![flow chart](https://github.com/user-attachments/assets/c0df60b1-02af-4c63-a421-e0dc678db5ec)
## 💡 Use Cases
- Accessibility enhancement
- Human-computer interaction
- Elderly care & fall-risk monitoring

## ⚠️ Limitations
- Not real-time (slow inference)
- Tested on limited egocentric data
- CPU-only; no GPU acceleration

## 👨‍💻 Author
Deep Das | [LinkedIn](https://www.linkedin.com/in/deep-das-446405301/) | [GitHub](https://github.com/DEEP-11-DAS)
