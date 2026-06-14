<div align="center">

# 🕌 DeenSphere
### **The Ultimate AI-Powered Islamic Lifestyle Ecosystem**

[![Platform](https://img.shields.io/badge/Platform-Flutter-blue?style=for-the-badge&logo=flutter)](https://flutter.dev/)
[![Language](https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart)](https://dart.dev/)
[![Backend](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![API](https://img.shields.io/badge/API-Express.js-000000?style=for-the-badge&logo=express)](https://expressjs.com/)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql)](https://www.mysql.com/)
[![AI](https://img.shields.io/badge/AI-Gemini-blueviolet?style=for-the-badge&logo=google-gemini)](https://deepmind.google/technologies/gemini/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Empowering the Ummah with cutting-edge AI, a Halal marketplace, and a global community.**

---

</div>


---


## 📖 Overview
**DeenSphere** is more than just an Islamic app; it's a comprehensive digital companion for the modern Muslim. Developed with devotion at **Softece**, it bridges the gap between traditional practice and modern technology. Using **Google Gemini AI**, DeenSphere provides instant Islamic guidance and knowledge, while the integrated marketplace and community platform foster a connected and prosperous Ummah.

---

## ✨ Key Features
- 🤖 **AI Islamic Assistant:** Instant answers to Islamic queries powered by Google Gemini.
- 📖 **Quran Explorer:** Digital Quran with multiple translations, recitations, and bookmarks.
- 🕋 **Prayer & Qibla:** Accurate prayer timings and a precise Qibla compass based on location.
- 🛒 **Halal Marketplace:** Buy and sell Islamic books, clothing, and prayer essentials.
- 🤝 **Ummah Community:** Share posts, Islamic reminders, and connect with other Muslims.
- 📅 **Islamic Calendar:** Hijri dates, important Islamic events, and daily Sunnah tasks.
- 🛡️ **Admin Panel:** Comprehensive management of users, sellers, and community moderation.

---

## 📁 Project Structure

The ecosystem is designed with a modular architecture:

### 🕌 1. DeenSphere (User App)
The primary interface for users, providing spiritual tools and social features.
```text
DeenSphere/app/src/main/java/com/deensphere/softece/
├── 🤖 ai/           # Gemini AI integration & Islamic guidance
├── 📖 quran/        # Quranic text, audio recitations & translations
├── 🕋 prayer/       # Prayer times, Qibla compass & Adhan settings
├── 🛒 market/       # Halal Marketplace, cart, and order tracking
├── 🤝 community/    # Social hub, post creation, and comments
├── 🏠 home/         # Dynamic dashboard with daily Ayats & reminders
├── 👤 profile/      # User account, progress & settings management
└── 🛠️ utils/        # Firebase helpers & shared components
```

### 🛡️ 2. Admin (Management App)
The control center used to moderate the platform and verify marketplace transactions.
```text
Admin/app/src/main/java/com/deensphere/softece/admin/
├── 👥 User/         # User database management
├── 🏬 Seller/       # Seller profiles & verification
├── 📦 Market/       # Marketplace moderation & approvals
├── 🔑 Auth/         # Secure administrative access
└── 📊 Analytics/    # System usage & community growth monitoring
```

---

## 🏗️ Core Project Sections

### 🛡️ 1. Admin Control Center
*The nerve center for system-wide management and verification.*
> [!NOTE]
> Screenshots will be added once the UI implementation is complete.

---

### 🔑 2. Secure Access Flow
*A seamless, secure authentication experience for all users.*
*(Registration, Login, and Password Recovery)*

---

### 🏠 3. Intelligent Dashboard
*Dynamic home screen featuring daily Ayats, Hadiths, and upcoming prayer times.*

---

### 📖 4. Quran & Spiritual Tools
*Immersive Quran reading experience and spiritual growth tracking.*

---

### 🤝 5. Global Ummah Hub
*Connect with the community, share knowledge, and grow spiritually together.*

---

### 🛒 6. Halal Marketplace
*A secure, peer-to-peer e-commerce platform for Islamic products.*

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Languages** | Java (JDK 17) |
| **Backend** | Firebase (Real-time DB, Auth, Firestore, Storage, Cloud Messaging) |
| **AI Engine** | Google Gemini API (`generativeai:0.9.0`) |
| **Maps** | OpenStreetMap (osmdroid) for Mosque Finder |
| **UI/UX** | Material Design 3, Lottie Animations, Facebook Shimmer |
| **Image Loading** | Glide |
| **Architecture** | MVC / MVVM with WorkManager for background tasks |

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>DeenSphere</i>
</p>
