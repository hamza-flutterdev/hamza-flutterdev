<div align="center">

# Hey, I'm Hamza Shahid 👋
### Flutter Developer building offline-first, AI-powered mobile apps

📍 Islamabad, Pakistan &nbsp;•&nbsp; 🏢 Junior Flutter Developer @ Teramob Technologies

[LinkedIn](https://linkedin.com/in/hamza-flutterdev) • [GitHub](https://github.com/hamza-flutterdev) • [Email](mailto:hamzabutthb553.hb@gmail.com)

</div>

---

## About Me

I ship production Flutter apps — not demos. In a bit over a year at **Teramob Technologies**, I've taken **15+ apps** from architecture to the Play Store, contributed to another 5–10, and collectively they've crossed **150,000+ downloads**. I've also published my own Flutter package on pub.dev and worked on a second one alongside a teammate.

What I actually care about: **offline-first data design** (so apps work when the network doesn't), **clean, testable architecture**, and **AI features that feel native** rather than bolted on. I write my core logic in **Dart and C++**, and direct/debug native modules when a feature needs to reach outside Flutter.

<div align="center">

| 🚀 15+ Apps Shipped | 📲 150,000+ Downloads | ⏱️ 1+ Years in Production |
|:---:|:---:|:---:|

</div>

---

## 🚀 What I Do

- 📱 Build **cross-platform mobile apps**
- 🗄️ Design **offline-first data layers** with encrypted storage
- 🔥 Integrate **Firebase** (Auth, Firestore, Realtime DB, Remote Config, Analytics, Crashlytics)
- 🤖 Add **AI features**
- 🔧 Direct and debug **native platform-channel modules**
- 💰 Implement **full monetization** — Google Mobile Ads, In-App Purchases, Remote Config–driven ad control
- 📦 Build and publish **Flutter packages** for reuse across projects
- 🎨 Craft **responsive, animated UI** 

---

## 🛠️ Tech Stack

**Languages**
`Dart` • `C++`

**State Management & Architecture**
`GetX` • `Riverpod` • `BLoC` • `Provider` • `Clean Architecture` • `MVVM` • `Dependency Injection`

**Backend & Cloud**
`Firebase` (Auth, Firestore, Realtime DB, Remote Config, Crashlytics, Analytics) • `REST APIs` • `OneSignal`

**Data & Storage**
`SQLite (sqflite)` • `flutter_secure_storage` • `SharedPreferences` • `AES-GCM asset encryption`

**Native Integration**
Android & iOS platform-channel modules (Kotlin/Swift) — implemented with AI-assisted coding, directed and debugged using core Dart/C++ understanding

**Testing & Quality**
`flutter_test` (Unit, Widget, Integration) • Breakpoint debugging • Code review & performance profiling (jank, memory leaks, cold-start)

**UI/UX**
`Material Design 3` • `Lottie` • `Shimmer` • Custom widgets • Responsive design

**Monetization & Analytics**
`Google Mobile Ads` • `In-App Purchases` • `Firebase Analytics` • `OneSignal Push Notifications`

**Tools & Workflow**
`Android Studio` • `VS Code` • `Git/GitHub` • `Google Play Console` • `pub.dev` • `Postman` • `Figma` • `Photoshop` • `CI/CD (GitHub)`

---

## 🎯 Featured Projects

*the ones I'd actually walk you through.*

### 🚦 [UK Driving Test Preparation](https://play.google.com/store/apps/details?id=com.ma.drivingtestprepration)
Offline-first UK driving theory app — Highway Code reader, topic-based quizzes, case studies, and a reaction-time test, backed by an **AES-GCM encrypted local database**.

- 📖 Searchable Highway Code reader, quizzes with review & progress tracking, traffic sign reference
- 🔒 Encrypted SQLite + assets, with the key delivered through a native Android/iOS key-provider module — directed and debugged to resist reverse engineering
- 🐍 Content sourced and cleaned from official UK Highway Code material via Python scripts
- 🔔 Local notifications, deferred quiz reminders, and cached video downloads
- 🔥 Firebase (Crashlytics, Analytics, Remote Config, Firestore) • OneSignal • In-app purchases • Ads

**Tech**: Flutter (Riverpod codegen, Freezed), Python, sqflite, `flutter_secure_storage`, Firebase

---

### 📘 [Learn English Speaking](https://play.google.com/store/apps/details?id=com.unisoftaps.learnenglishfromurdu)
Offline English-learning app for Urdu speakers — **100,000+ downloads** on the Play Store.

- 📚 Vocabulary and grammar modules backed by a local SQLite database
- 🤖 AI-assisted dictionary lookup
- 🗣️ Text-to-speech for pronunciation practice
- 💾 Fully offline access

**Tech**: Flutter, GetX, SQLite, Google TTS, Firebase

---

### 📐 [AI Maths Teacher](https://play.google.com/store/apps/details?id=com.mathequations.solvemathsproblems)
Camera and manual-input math solver that generates AI-powered, step-by-step solutions.

- 📷 Camera-based equation recognition (`image_picker`, `image_cropper`)
- ⌨️ Custom equation input built on a **forked and modified `math_keyboard` package**
- 🤖 AI-generated step-by-step explanations
- 📚 Offline formula library
- 🔥 Firebase Remote Config & Analytics

**Tech**: Flutter, AI API, `math_keyboard_fork` (forked), Firebase

---

### 🎓 [F5 CS Notes](https://play.google.com/store/apps/details?id=com.btechno.codenamehasan)
Computer science exam-prep app with MCQs, short-answer practice, and an AI tutor.

- 📝 MCQ and short-answer practice with result history
- 🤖 Built-in AI tutor for on-demand help
- 🔐 Firebase Auth & Firestore for accounts and content
- 🛡️ Screenshot / screen-recording prevention to protect paid content
- 💰 Premium subscription system with chapter locking and in-app purchases

**Tech**: Flutter, GetX, Firebase Auth/Firestore, AI API integration

---

<details>
<summary><strong>📂 More projects</strong></summary>

<br>

### 🌍 World Explorer
Real-time interactive Earth explorer with maps, earthquake tracking, and location insights.
- Interactive Google Maps with country insights & nearby amenities
- WebSocket-based real-time earthquake alerts
- Live weather & compass features
- Firebase (Remote Config, Analytics, Crashlytics) • Full monetization (Ads + IAP)

*Tech: Flutter, WebSockets, Google Maps API, Firebase, OneSignal*

### 🎨 Chat Sticker — WhatsApp Sticker Maker
Sticker creation app with built-in, AI-generated, and custom gallery stickers.
- Image editing, compression, and export to WhatsApp
- AI-generated stickers
- Animated, responsive UI (Riverpod, Lottie, Shimmer)
- Firebase Remote Config for ad control

*Tech: Flutter, Riverpod, image processing, Firebase*

### 🇯🇵 Learn Japanese Speaking
Language-learning app covering Hiragana, Katakana, Kanji, and JLPT prep.
- Structured SQLite + JSON for robust offline support
- AI dictionary & translation, speech-to-text and text-to-speech
- Quizzes, progress tracking, analytics, dark mode with Lottie

*Tech: Flutter, SQLite, AI APIs, Firebase, OneSignal*

### ☁️ Weather Apps Series
Four region-specific weather apps, each an iteration on architecture, performance, and monetization.
- **Estonia Weather** — native Android widget via platform channels, hourly/7-day forecasts, geolocation
- **Tonga Weather** — dynamic animated backgrounds, OneSignal push notifications, Remote Config + Ads
- **Honduras Weather** — native ads + maps integration, batch weather loading, Analytics & Crashlytics
- **Malta Weather** — minimalist gradient UI, performance-optimized, smooth transitions

*Tech: Flutter, GetX, Kotlin, REST APIs, Firebase, OneSignal, Platform Channels*

### 🎯 GK Quiz App
22-screen educational quiz app with AI integration.
- AI-powered assistance (Google Gemini) and speech recognition
- Progress analytics with visual charts
- Google Mobile Ads

*Tech: Flutter, GetX, SQLite, Firebase, Google AI*

</details>

---

## 📦 Package Development

I've worked on two published pub.dev packages, plus a fork for internal use:

| Package | Description | Stats |
|---|---|---|
| 🎹 [**flutter_multilingual_keyboard**](https://pub.dev/packages/flutter_multilingual_keyboard) | My own package, published solo — an in-app Urdu/English keyboard, architected to scale to more languages via fork | 37 downloads · 150 pub points |
| 📢 [**smart_ads_manager**](https://pub.dev/packages/smart_ads_manager) | Worked on this one with a teammate — streamlines ad-network integration across our Flutter apps | 140 downloads · 120 pub points |
| ⌨️ **math_keyboard_fork** | Forked and modified `math_keyboard` to support custom equation input for AI Maths Teacher | Powers a live production app |

---

## 💼 Professional Experience

**Junior Flutter Developer** · Teramob Technologies
*Aug 2025 – Present | Rawalpindi, Pakistan*
- Delivered **15+ production Flutter apps** and contributed features/fixes to 5–10 more, using GetX, Riverpod, and BLoC — collectively **150,000+ downloads** on the Play Store
- Built and customized Flutter packages, reused across projects to cut new-feature bootstrap time
- Profiled and resolved performance issues — jank, memory leaks, slow cold-start
- Participated in code reviews and architecture discussions, keeping standards consistent across projects
- Refactored existing apps (e.g., Noorani Qaida) for better maintainability

**Flutter Developer Intern** · Teramob Technologies
*May 2025 – Aug 2025*
- Built 6 full-scale apps implementing GetX state management, SQLite persistence, and native Android platform-channel integrations under senior mentorship
- Promoted to Junior Developer at the end of the internship

<details>
<summary>Before Flutter</summary>
<br>

**Customer Interaction Officer** · Clean & Green Services *(Oct 2023 – Oct 2024)* — Managed client communications, quotations, and CRM records.

</details>

---

## 📚 Education

🎓 **Bachelor of Science in Data Science (BS-DS)** — Virtual University *(In Progress)*
🎓 **Bachelor of Commerce (B-Com)** — Allama Iqbal Open University *(2025)*
🎓 **Intermediate in Computer Science (ICS)** — Federal Board (FBISE) *(2019)*

## 🏆 Certifications

✅ UI/UX Fundamentals (2022)

---

## 📫 Let's Connect!

💼 **[LinkedIn](https://linkedin.com/in/hamza-flutterdev)**
💻 **[GitHub](https://github.com/hamza-flutterdev)**
📧 **[hamzabutthb553.hb@gmail.com](mailto:hamzabutthb553.hb@gmail.com)**
---

<div align="center">

💡 *I'm passionate about building impactful mobile experiences — and open to opportunities where I can grow my expertise and deliver real value through technology.*

**🚀 Let's build something amazing together!**

</div>
