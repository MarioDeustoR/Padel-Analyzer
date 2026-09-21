# 🎾 Padel Analyzer PRO - System Architecture & PRD

> **📌 Repository Note:** This repository does not contain source code. It is a comprehensive **Product Requirements Document (PRD)** and System Architecture blueprint for an AI-powered sports coaching application. It showcases full software lifecycle planning, risk management, and Agile project coordination.

## 📖 Product Vision
**Padel Analyzer PRO** was conceptualized to democratize elite sports training. Using computer vision and machine learning, the app acts as a "coach in your pocket," reading player movements frame-by-frame to generate virtual skeletons, analyze stroke technique, and provide immediate biomechanical feedback.

## 👨‍💻 My Role: Project Lead & Tech Coordinator
I led a cross-functional team of 5 members, taking ownership of the product's technical direction and lifecycle:
* **System Architecture:** Designed the technical pipeline integrating **Google MediaPipe** (33 keypoints estimation) to calculate joint angles, relative distances, and reaction times.
* **Agile Management:** Coordinated sprints, Epics, and task delegation using **Jira** and Gantt charts to ensure milestone delivery.
* **Risk Mitigation:** Developed strict contingency plans for potential technical bottlenecks, including Cloud GPU processing costs and AI model accuracy thresholds (maintaining an MVP fallback if accuracy dropped below 75%).
* **Database Modeling:** Architected relational database schemas (Entities: `Video`, `Level`, `Movement`) to efficiently link player telemetry with an intelligent educational content recommendation system.

## 🛠️ Conceptual Tech Stack
* **AI & Computer Vision:** Google MediaPipe (Pose Estimation).
* **Project Management:** Jira, Agile Methodology, Gantt Charts.
* **Infrastructure Planning:** Cloud-based GPU processing, Relational Databases (N:M interrelations).
* **UI/UX:** Gamification loops, Heatmaps, and Interactive Telemetry Overlays.
