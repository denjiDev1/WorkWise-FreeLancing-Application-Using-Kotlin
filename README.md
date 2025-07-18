# 💼 WorkWise – Freelancing Platform (Android, Kotlin)

**WorkWise** is a full-featured freelancing mobile application inspired by platforms like Fiverr and Upwork. It connects clients and freelancers through a seamless hiring and project execution system — all built using **Kotlin** for Android. The app provides real-time messaging, skill-based profiles, secure hiring workflows, and job posting capabilities.

---

## 🚀 Features

- 🧑‍💻 **Freelancer Profiles** with bio, skills, hourly rate, and rating
- 📄 **Job Posting & Bidding** by clients
- 💬 **Real-time Chat** between freelancers and clients
- 🧾 **Proposal Management** for easy hire/decline interactions
- 💼 **Order Tracking** from hiring to completion
- 🌐 **Category-wise Browsing** of jobs and freelancers
- 📥 **Wallet/Transaction View** *(mocked in prototype phase)*
- 🔒 **Authentication** (Login, Register, JWT-based sessions)
- 🪙 **Top Earners Leaderboard** (based on ratings or completed projects)

---

## 🛠️ Tech Stack

- **Language**: Kotlin  
- **Architecture**: MVVM  
- **UI Toolkit**: Jetpack Compose  
- **Backend**: Firebase (Authentication & Firestore)  
- **State Management**: LiveData + ViewModel  
- **Navigation**: Jetpack Navigation Component  

---

## 📱 Screenshots

| Freelancer Feed | Proposal View | Chat System |
|------------------|----------------|-------------|
| ![Feed](/screens/feed.png) | ![Proposal](/screens/proposal.png) | ![Chat](/screens/chat.png) |

> 📸 *More available in the case study PDF.*

---

## 📂 Folder Structure

```
WorkWise/
├── app/
│   ├── activities/
│   ├── viewmodels/
│   ├── models/
│   ├── adapters/
│   ├── utils/
│   └── firebase/             # Firestore and Auth services
├── res/
│   ├── layout/
│   └── drawable/
├── case_study.pdf            # 📘 Project process documentation
├── build.gradle
└── README.md
```

---

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/WorkWise.git
   ```

2. Open the project in **Android Studio**.

3. Add your Firebase configuration file (`google-services.json`) in `app/`.

4. Sync Gradle and Run the app on Android Emulator or Device.

---

## 🧪 Use Case

> "Allow clients to easily post freelance jobs and hire vetted freelancers via a mobile-first platform."

---

## 📘 Case Study

📎 **`case_study.pdf`** — Included in the root directory.

It covers:
- Project Overview & Challenges
- Architecture Diagram
- Workflow & Navigation Flow
- Screenshots
- Future Improvements

---

## ✨ Future Enhancements

- In-app payments via Stripe/PayPal
- Ratings & Review System
- Advanced Filtering (by price, rating, recency)
- Push Notifications for chat/job invites
- Project milestones and delivery confirmations

---

## 🤝 Contributing

Contributions, bug reports, and suggestions are welcome!  
Please open issues or submit a pull request.

---

## 📜 License

MIT License © 2025 WorkWise Devs

---
> 💼 *Connecting talent with opportunity — one job at a time.*
