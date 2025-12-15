# SteadyLoop ♾️

> **"A Flight Recorder for the Bipolar Brain."**

**SteadyLoop** is a minimalist, privacy-first Progressive Web App (PWA) designed strictly for managing Bipolar Type 1 & 2. It prioritizes speed, clinical clarity, and zero-friction logging over social features or gamification.

[![Project Status](https://img.shields.io/badge/status-live_beta-success)](https://steady-loop-v1.vercel.app/)
![Tech Stack](https://img.shields.io/badge/stack-Next.js_16_|_Supabase_|_Tailwind-blue)
![Platform](https://img.shields.io/badge/platform-PWA_|_Mobile_First-purple)


## 💡 The Philosophy (Why I Built This)

Most mental health applications suffer from "feature bloat"-gamification, social feeds, and complex charts that are overwhelming when a user is in a crisis.

**SteadyLoop** was built to solve a specific UX problem: **Speed.**

I wanted to engineer a tool that removes all friction between the user and the database. The goal was to create a "Flight Recorder" that captures critical health data in under 5 seconds, ensuring adherence even in high-stress scenarios.

## ⚡ The Logic (The "Zero Friction" Philosophy)

When a user is manic or depressed, they do not want to see charts, ads, or "streaks." They need to log data in seconds and get out.

* **Clinical Scale:** Refactored from arbitrary ratings to a strict clinical scale (1=Depression, 3=Stable, 5=Mania).
* **Visual Intelligence:** Raw data is instantly converted into a 7-Day Trend Line, using gradient visualizations to signal shifts towards Mania (Red) or Depression (Blue) relative to a "Stable" baseline.
* **Smart Cabinet:** A dynamic medication system that handles "Daily" vs "As Needed" (PRN) doses, complete with undo logic for accidental logs.
* **Native PWA:** Configured with a full manifest and iOS meta-tags. Installable on any device with zero browser chrome, functioning exactly like a native app.
* **Nuclear Option:** A complete data-wipe feature. Privacy is paramount; if the user wants out, the data is gone from the server instantly.

## 🛠️ The Tech Stack

This is not just a CRUD app; it is a real-time PWA built for reliability and speed on the absolute latest standard.

* **Framework:** [Next.js 16](https://nextjs.org/) (App Router, Server Actions, React 19)
* **Database & Auth:** [Supabase](https://supabase.com/) (PostgreSQL + Row Level Security)
* **Visualization:** Recharts (Custom SVG plotting)
* **Styling:** Tailwind CSS + Shadcn UI (Dark Mode Default)
* **Architecture:**
    * **PWA:** `manifest.json` + iOS Meta Tags for "Add to Home Screen" support.
    * **Optimistic UI:** The interface updates instantly while the database writes in the background.

## 🔒 License & IP

**SteadyLoop** is proprietary software.

* **The Code:** The source code is hosted in a private repository to protect the intellectual property and user safety logic.
* **The Purpose:** This repository serves as the public documentation, issue tracker, and roadmap.

## 🚀 Roadmap & Future Features
**Current Status:** v1.0 (Core Logging & Visualization Complete)

Phase 2 (In Development) focuses on Data Sovereignty and the Safety Net:
* **PDF/CSV Export:** Generating a clinician-ready report for psychiatrist appointments.
* **Safety Net Automation:** Automated server-side monitoring for user activity to ensure proactive crisis outreach and adherence support.

---

### 👨‍💻 Author

**Timothy Finomo**
*Frontend Developer & Support Specialist | Lagos, Nigeria*

Building tools that keep people safe.

[<img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin">](https://www.linkedin.com/in/timothy-finomo-522bb1241/)
[<img src="https://img.shields.io/badge/Portfolio-View_Work-black?style=flat&logo=vercel">](https://steady-loop-v1.vercel.app/)

---
## 🖼️ Application UI Showcase

### Light Mode

| Screenshot 1 | Screenshot 2 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/5d7be83a-54bd-46ad-8644-ae4c42a13d80" width="100%" alt="Light Mode Screenshot 1" /> | <img src="https://github.com/user-attachments/assets/95c9607f-3986-4aa4-9c55-cc61afb07036" width="100%" alt="Light Mode Screenshot 2" /> |

| Screenshot 3 | Screenshot 4 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/d2bd23d8-411b-4d0e-a3e5-0a5e2dde9f98" width="100%" alt="Light Mode Screenshot 3" /> | <img src="https://github.com/user-attachments/assets/9d79637f-19d3-42ca-bdea-d27e33a22af0" width="100%" alt="Light Mode Screenshot 4" /> |

### Dark Mode

| Screenshot 5 | Screenshot 6 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/06dcbf14-eff-4557-a094-c008ef298ac2" width="100%" alt="Dark Mode Screenshot 1" /> | <img src="https://github.com/user-attachments/assets/615d5b17-b8b4-4d61-9926-227d56d3619f" width="100%" alt="Dark Mode Screenshot 2" /> |

| Screenshot 7 | Screenshot 8 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/177b5d54-ff3c-41d6-b245-207e96c36351" width="100%" alt="Dark Mode Screenshot 3" /> | <img src="https://github.com/user-attachments/assets/cc4529ba-8392-405e-891b-039ea05b730a" width="100%" alt="Dark Mode Screenshot 4" /> |











