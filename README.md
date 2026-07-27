# MedGuard-AI

**MedGuard AI** is an intelligent, multimodal clinical safety web application built with Next.js and powered by Google’s Gemini AI. It acts as a 24/7 personal pharmacist designed to proactively prevent dangerous drug-drug and food-drug interactions, making medication management safer and more accessible for patients and caregivers.

## 🚀 Live Demo
*(Insert your live Vercel URL here once it finishes deploying, e.g., https://medguard-ai.vercel.app)*

---

## ✨ Core Features

*   📸 **LabClear Vision Scanning:** Upload a photo of a loose pill, pharmacy receipt, or medication label. Using Gemini’s multimodal vision capabilities, the app extracts the chemical data and identifies the medication to flag severe conflicts.
*   🕒 **Smart Spacing Schedule Generator:** Input your daily prescriptions, and the clinical scheduling engine will automatically generate an optimized, conflict-free 24-hour timeline to space out interacting medications.
*   🧮 **Deterministic DoseGuide:** Ensures mathematical reliability by utilizing hard-coded JavaScript logic for weight-based dosage calculations, eliminating the risk of AI hallucinations in critical medical math.
*   🔊 **Voice Dosage Assistant (Read Aloud):** Built with accessibility in mind, the platform uses browser speech synthesis to read dosage instructions and interaction warnings out loud for visually impaired users or busy caregivers.

---

## 🛠️ Tech Stack

*   **Frontend:** Next.js (React), Tailwind CSS
*   **AI Integration:** Google Gemini 1.5 Flash API (Text & Multimodal Vision)
*   **Deployment:** Vercel

---

## ⚙️ Local Setup & Installation

If you want to run this project locally on your machine, follow these steps:

**1. Clone the repository:**
```bash
git clone [https://github.com/mohizqazi1994-dotcom/MedGuard-AI.git](https://github.com/mohizqazi1994-dotcom/MedGuard-AI.git)
cd MedGuard-AI
