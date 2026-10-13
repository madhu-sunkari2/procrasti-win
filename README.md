# 🧠 Procrasti-WIN — The Procrastination Assistant

> **Make avoiding work accidentally productive with AI.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://procrasti-win-796910223127.us-central1.run.app)
[![Built with Gemini](https://img.shields.io/badge/AI-Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero_Vanilla_JS-success?style=for-the-badge)](https://developer.mozilla.org/)

---

## 🚀 Live Application
👉 **[Open Procrasti-WIN Live](https://procrasti-win-796910223127.us-central1.run.app)**

---

## 💡 The Core Concept

Procrastination is almost never laziness—it is **emotional regulation failure** (fear of failure, executive dysfunction, dopamine depletion, or perfectionism). 

When avoiding work, people naturally engage in "productive avoidance" (cleaning, organizing, browsing Wikipedia). **Procrasti-WIN hijacks this impulse**:

1. You tell it what task you're running away from (e.g. *"Write Master's Thesis"*, *"2025 Tax Returns"*).
2. You select your current energy vibe (😴 **Dead**, 😐 **Meh**, ⚡ **Hyped**, 😰 **Anxious**).
3. The AI diagnoses your psychological resistance and serves **5 tailored detour tasks** that are secretly productive and related to your goal:
   - *"Watch 1 YouTube explainer"* ➔ **Secretly: Conceptual Research (+20%)**
   - *"Complain to a friend about the hardest part"* ➔ **Secretly: Rubber Duck Debugging (+25%)**
   - *"Draft an intentionally ugly 3-bullet summary"* ➔ **Secretly: Blank-Canvas Defrosting (+25%)**
   - *"Clean your desk for 7 minutes"* ➔ **Secretly: Visual Cortisol Reduction (+15%)**

---

## ✨ Features

### 1. 🎯 Accidental Productivity Converter
* Check off detour tasks to reveal their secret productivity value.
* Real-time progress bar shows how much foundational work was secretly accomplished.
* Synthesized Web Audio dopamine pings and zero-dependency Canvas confetti bursts upon completion.

### 2. ⚡ Vibe Check System
* **😴 Dead**: Passive intake tasks requiring near-zero willpower.
* **😐 Meh**: Low-friction environmental and setup tasks.
* **⚡ Hyped**: Fast-paced, chaotic brain dump sprints.
* **😰 Anxious**: Low-stakes de-escalation actions to defeat perfectionism.

### 3. ⏱️ The 2-Minute Gateway Trick
* Overcomes inertia by generating laughably tiny 120-second first steps (*"Just open the blank doc and type 3 words"*).

### 4. 🔥 Live AI Guilt-O-Meter & Roasts
* Floating dock widget tracking avoidance time in real-time.
* At 100% maximum guilt, fires loving, satirical roasts (*"You've been in 'prep mode' so long you're now a qualified architectural surveyor of your own desk"*).
* 1-click **Share Roast on X / Twitter** button.

### 5. 🧩 Procrastination Personality Quiz
* 4-question interactive diagnostic classifying users into 4 archetypes (MBTI style):
  * **The Dreamer** (Visionary Drifter)
  * **The Perfectionist** (Hyper-Scrutinizer)
  * **The Overwhelmed** (System Overload)
  * **The Rebel** (Strategic Defiant)
* Generates a shareable card with secret strengths, fatal flaws, and custom detours.

### 6. 🛋️ AI Therapist Mode (*Dr. Delay, Psy.D.*)
* Conversational chat interface to analyze your brain's excuses.
* Humorously deconstructs irrational guilt and concludes every session with **exactly one atomic 60-second micro-step**.

### 7. 📣 Social Shame & Public Accountability
* Generates weaponized commitment tweets granting public permission to roast your life choices if your task is not finished by midnight.

### 8. 📜 Hall of Delay (History Wall)
* Persistent history stored in browser `localStorage`.
* Aged tasks automatically earn satirical clearance (*"Paprika expired; universe solved problem"*).

---

## 🛠️ Tech Stack

* **Frontend**: Pure Vanilla HTML5, CSS3, Modern JavaScript (ES6+).
* **AI Engine**: Google Gemini API integration with automatic fallback to an intelligent offline heuristic engine.
* **Animations & Audio**: HTML5 Canvas Confetti engine + Web Audio API frequency synthesizer (no external CDNs or heavy packages).
* **Styling**: Responsive dark-mode glassmorphism design with CSS variables.
* **Deployment**: Docker + Nginx on Google Cloud Run.

---

## 💻 Local Development

Run the app locally with zero setup:

```bash
# Clone the repository
git clone https://github.com/madhu-sunkari2/procrasti-win.git
cd procrasti-win

# Serve with any static web server (e.g., Python)
python3 -m http.server 8080
```
Open `http://localhost:8080` in your browser.

---

## 🐳 Docker Deployment

```bash
# Build Docker image
docker build -t procrasti-win .

# Run container
docker run -p 8080:8080 procrasti-win
```

---

## 🔑 Gemini AI Configuration (Optional)
The application works **100% offline out-of-the-box**. 

If you want live dynamic LLM responses from Google Gemini:
1. Click the **⚙️ API** button in the header.
2. Enter your Gemini API key (stored securely and privately in your browser's `localStorage`).

---

## 📄 License
MIT License. Feel free to use, modify, and build upon this project.
