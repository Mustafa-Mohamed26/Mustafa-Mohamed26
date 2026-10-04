<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=00BFFF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Mustafa+Mohamed+%F0%9F%91%8B;Flutter+%26+Mobile+Developer;I+build+real+products+that+run+in+production" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/mustafa-mohamed-095301318/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:mustafamohameda447@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **Flutter & Mobile Developer** from **Alexandria, Egypt**.

I don't just build apps — I build systems. My focus is on **production-grade** mobile development: real users, real data, real problems. I apply **Clean Architecture** on everything I touch — strict layer separation, dependency injection, and testable code by default.

What I enjoy most is taking a complex problem (like an AI agent managing a cardiology clinic's WhatsApp, or an AR lab that identifies chemical compounds) and turning it into clean, maintainable software.

- 🧱 **Architecture:** Clean Architecture · BLoC/Cubit · Repository Pattern · injectable + get_it
- ☁️ **Backend:** Firebase Cloud Functions (TypeScript) 
- 🤖 **AI in production:** Shipped a real Gemini-powered conversational agent
- 🥽 **AR/XR:** Flutter ↔ Unity bridge for augmented reality apps
- 📍 **Location:** Alexandria, Egypt · Open to remote work & collaboration

---

## 🚀 Projects

### 🏥 Dr. Ahmed Soliman Cardiology Clinics Ecosystem

> A full-stack, **production-deployed** clinic management system for a real cardiology clinic in Egypt.

**The idea in one sentence:** A patient sends a WhatsApp message → a Gemini AI agent replies, books appointments, and handles emergencies — all while the doctor watches everything update live on a Flutter dashboard.

**What makes it interesting:**

- **WhatsApp AI Agent** — a Gemini-powered bot that speaks Arabic and English, manages the full booking flow via a state machine, detects emergencies, and hands off to staff when needed. The AI is **constrained to 8 tools** — it cannot hallucinate or act outside its defined scope.
- **Flutter Web Dashboard** — real-time inbox, daily schedule, patient records, AI action review panel, emergency alerts. Every write from the backend reflects on the dashboard instantly via Firestore streams.
- **Security-first** — HMAC-SHA256 webhook verification, role-based Firestore rules, PHI-safe logging, encrypted local cache purged on logout.

```
Patient WhatsApp message
  → Firebase Webhook  (signature verified)
  → Pipeline          (idempotency · rate limit · patient lookup)
  → Gemini Orchestrator (8 guarded tools)
  → Firestore         (booking created / alert fired)
  → Flutter Dashboard (live update) ✓
```

**Stack:** `Flutter` · `Dart` · `BLoC` · `Firebase` · `Firestore` · `Cloud Functions` · `TypeScript` · `Google Gemini` · `WhatsApp Business API` · `Clean Architecture`

---

### 🔬 AR Chemistry Laboratory _(Graduation Project)_

> A Flutter + Unity augmented reality app that brings chemistry to life — point your camera at a marker, and watch a 3D molecule appear in real space. AI identifies the compound and provides information about it.

**What makes it interesting:**

- **Flutter ↔ Unity bridge** — the mobile shell is Flutter; the 3D AR environment runs inside Unity via `flutter_unity_widget`, with bidirectional communication between the two
- **AI compound recognition** — the app uses a machine learning model to identify chemical compounds from the camera feed
- Full AR interaction: rotate, zoom, and explore molecular structures in real space

**Stack:** `Flutter` · `Unity` · `AR Foundation` · `flutter_unity_widget` · `AI/ML`

---

## 🛠️ Tech Stack

**Mobile & Architecture**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![BLoC](https://img.shields.io/badge/BLoC%2FCubit-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)

**Backend & Cloud**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

**AI & APIs**

![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![WhatsApp API](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

**Workflow**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)


---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Mustafa-Mohamed26&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00BFFF&icon_color=00BFFF" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mustafa-Mohamed26&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=00BFFF&text_color=ffffff" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Mustafa-Mohamed26&theme=radical&hide_border=true&background=0d1117&ring=00BFFF&fire=00BFFF&currStreakLabel=00BFFF" />

</div>

---

<p align="center">
  <i>I build apps that solve real problems — not just portfolio pieces.</i><br/>
  <b>Open to freelance, remote roles, and collaboration.</b><br/>
  <sub>📍 Alexandria, Egypt · UTC+2</sub>
</p>

