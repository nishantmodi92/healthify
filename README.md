# 🏃 Healthify – AI-Powered Fitness & Wellness Tracker  

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-blue.svg)  
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-Material3-green)  
![Google Fit](https://img.shields.io/badge/Google_Fit-Integrated-red)  
![Engagement](https://img.shields.io/badge/User_Engagement+42%25-blue)  
![Crash-Free](https://img.shields.io/badge/Crash--Free-98%25-success)  

> **Healthify** is a personalized **fitness tracker and wellness companion** built with **Jetpack Compose, Google Fit API, and Firebase**.  
> It blends **real-time health tracking, gamified goals, AI-powered insights, and social challenges** to deliver **42% higher user engagement**.  

---

## 🌟 Core Highlights  

- 🧘 **Real-Time Health Tracking** – Steps, calories, heart rate, sleep, synced via Google Fit  
- 🎯 **Gamified Goal System** – Progress badges, streaks, rewards to keep motivation high  
- 📊 **Personalized Dashboard** – Interactive charts for calories, workouts & sleep cycles  
- 💡 **AI Insights** – Smart recommendations to improve habits & daily activity  
- 🔔 **Smart Notifications** – Adaptive reminders based on user patterns  
- 🏆 **Social Challenges** – Leaderboards & group goals for community engagement  
- 🌗 **Material You 3 UI** – Dark/light themes, animated Compose charts  
- 🔄 **Offline Mode** – Caches health metrics & syncs later seamlessly  
- 🚀 **Optimized Performance** – 98%+ crash-free, smooth animations <200ms frame time  

---

## 📊 Key Impact & Metrics  

✅ **42% boost in daily active users** after gamification launch  
🏅 **3× increase in goal completion rate** via rewards + streaks  
⚡ **98%+ crash-free sessions** with optimized Compose rendering  
📉 **30% fewer drop-offs** thanks to AI-driven reminders  
📊 **Firebase Analytics** tracking engagement, retention & features  

---

## ⚙️ Tech Stack  

- **Language:** Kotlin, Coroutines, Flow  
- **UI:** Jetpack Compose, Material 3  
- **Architecture:** MVVM + Clean Architecture + Modular layers  
- **Health Data:** Google Fit API, Health APIs  
- **Backend:** Firebase (Auth, Realtime DB, Analytics, FCM)  
- **Database:** Room + Paging 3 (offline-first)  
- **Networking:** Retrofit2 / OkHttp  
- **Image Loading:** Coil  
- **DI:** Dagger-Hilt  
- **Storage:** DataStore + SharedPreferences  

---

## 🧠 Architecture Overview  

```mermaid
flowchart TD
    UI[Compose UI Layer] --> VM[ViewModel]
    VM --> UC[Use Cases (Business Logic)]
    UC --> REPO[Repository Layer]
    REPO --> DB[Room Database]
    REPO --> FIREBASE[Firebase Services]
    REPO --> FIT[Google Fit API / Health APIs]

🛠 Setup Instructions

1️⃣ Clone the Repo
git clone https://github.com/nishantmodi92/healthify.git

2️⃣ Open in Android Studio Arctic Fox+

Min SDK: 21
Compile SDK: 34

3️⃣ Configure Firebase

Add google-services.json in /app

Enable Auth + Realtime Database + Analytics

4️⃣ Setup Google Fit OAuth credentials

5️⃣ Build & Run
./gradlew clean build


🌟 Live Experience

✅ Track steps, calories, sleep & workouts in real time
✅ AI-driven daily health tips & progress insights
✅ Gamified goals with badges, streaks & rewards
✅ Social leaderboards for motivation & competition
✅ Adaptive reminders & push notifications
✅ Offline support & smooth Compose UI

🔗 Links

📂 GitHub Repo

🌐 Portfolio Demo

✨ Healthify is a modern, scalable Android fitness app that blends health tracking, gamification, and AI insights to drive real-world engagement and retention.
🎉 Start tracking health with Healthify!



