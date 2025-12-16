# SteadyLoop ♾️

> **"A Flight Recorder for the Bipolar Brain."**

**SteadyLoop** is a minimalist, privacy-first Progressive Web App (PWA) engineered strictly for the management of Bipolar Type 1 & 2. It prioritizes speed, clinical clarity, and zero-friction logging over social features or gamification.

[![Project Status](https://img.shields.io/badge/status-live_beta-success)](https://steady-loop-v1.vercel.app/)
![Tech Stack](https://img.shields.io/badge/stack-Next.js_16_|_Supabase_|_Tailwind-blue)
![Platform](https://img.shields.io/badge/platform-PWA_|_Mobile_First-purple)


## 💡 The Philosophy (Zero Friction)

Most mental health applications suffer from "feature bloat"—gamification, social feeds, and complex charts that create cognitive load during a crisis.

SteadyLoop was built to solve a specific UX problem: **Latency.**
The goal was to engineer a "Flight Recorder" that captures critical health data in under 5 seconds, ensuring adherence even in high-stress scenarios.

## ⚡ Core Architecture

### **1. The Clinical Scale**
Refactored from arbitrary "star ratings" to a strict clinical integer scale to map medical reality:
* `1` = Severe Depression
* `3` = Stable Baseline
* `5` = Mania

### **2. Visual Intelligence**
Raw data is instantly transmuted into a **7-Day Trend Line**. The system uses gradient visualizations to signal velocity shifts towards Mania (Red) or Depression (Blue) relative to the stable baseline, allowing for rapid pattern recognition.

### **3. The Smart Cabinet**
A dynamic medication inventory system handling "Daily" vs "As Needed" (PRN) doses. Includes optimistic UI updates and "Undo" logic to prevent database pollution from accidental logs.

### **4. Native PWA**
Configured with a robust `manifest.json` and iOS meta-tags. The application installs to the home screen with zero browser chrome, leveraging service workers for near-native performance.

### **5. The Nuclear Option (Data Sovereignty)**
Privacy is absolute. A hard-delete feature allows the user to wipe all associated rows from the database instantly.

## 🛠️ The Tech Stack

Built for reliability and speed on the Vercel Edge Network.

| Layer | Technology |
| :--- | :--- |
| **Framework** | **Next.js 16** (App Router, Server Actions, React 19 RC) |
| **Database** | **Supabase** (PostgreSQL + Row Level Security) |
| **Styling** | **Tailwind CSS** + Shadcn UI (Dark Mode Default) |
| **Visualization** | **Recharts** (Custom SVG plotting) |
| **Deployment** | **Vercel** (CI/CD Pipeline) |

**Key Engineering Features:**
* **Optimistic UI:** Interface updates instantly; database writes occur asynchronously.
* **Zod Validation:** Strict runtime type-checking for all inputs.
* **Server Actions:** Zero-API-route architecture for direct database mutations.

## 🔒 License & IP

**SteadyLoop is Proprietary Software.**

* **The Code:** The source code is hosted in a private repository to protect the intellectual property and user safety logic.
* **The Purpose:** This repository serves as the public documentation, issue tracker, and roadmap.

## 🚀 Roadmap & Future Features
**Current Status:** `v1.0 (Closed Beta)`

**Phase 2 (In Development):**
* [ ] **Clinical Export:** PDF/CSV generation for psychiatrist review.
* [ ] **The Safety Net:** Automated server-side inactivity monitoring (Dead Man's Switch).
* [ ] **Biometric Lock:** integrating WebAuthn for FaceID support.

---

### 👨‍💻 Author

**Timothy Finomo**
Lead Engineer, SteadyLoop.
*Building quiet tools for loud minds.*

[<img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin">](https://www.linkedin.com/in/timothy-finomo-522bb1241/)
[<img src="https://img.shields.io/badge/Product-black?style=flat&logo=vercel">](https://steady-loop-v1.vercel.app/)

## 📸 The "Quiet" UI System

### 🎥 Interaction Preview
### ☀️ Light Mode
| **Dashboard View** | **History List** |
| :---: | :---: |
|  |  |
| **Settings** | **Mobile Menu** |
|  |  |

### 🌙 Dark Mode (Default)
| **Dashboard View** | **History List** |
| :---: | :---: |
|  |  |
| **Settings** | **Trends Analysis** |
|  |  |
