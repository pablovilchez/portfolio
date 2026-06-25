<div align="center">
  <img src="https://github.com/pablovilchez/portfolio/blob/main/assets/mi_fortitu/mi_fortitu_banner.webp" alt="Mi Fortitu Banner" width="100%">
  
  <h1>Mi Fortitu 🛡️</h1>
  <p><strong>The ultimate mobile companion app for 42 School students.</strong></p>

  <a href="URL_APPLE_STORE"><img src="https://img.shields.io/badge/Download_on_the-App_Store-black?style=for-the-badge&logo=apple" alt="Download on App Store"></a>
  <a href="URL_GOOGLE_PLAY"><img src="https://img.shields.io/badge/Get_it_on-Google_Play-black?style=for-the-badge&logo=google-play" alt="Get it on Google Play"></a>

  <br><br>
</div>

## 📖 About The Project

**Mi Fortitu** is a comprehensive, full-stack mobile application designed exclusively for students of the **42 Network**. It serves as an enhanced mobile client for the 42 Intranet, providing students with a fast, native, and gamified experience to track their progress, manage campus life, and connect with peers.

Built with **Flutter** for a smooth cross-platform experience and powered by **Serverpod** for a robust, scalable Dart backend.

### ✨ Key Features

*   **🔐 42 Intra OAuth Integration**: Secure, seamless login using the official 42 API. No passwords stored, ever.
*   **📊 Comprehensive Dashboard**: Instant access to your core metrics: Level, Wallet (₳), Evaluation Points, and active Cursus progress.
*   **🤝 Campus & Coalitions**: Real-time visibility into your campus clusters, student locations, and coalition standings.
*   **📅 Slot Management**: Easily create and manage your evaluation slots directly from your phone. *(Note: Reserving evaluations is currently restricted by the 42 API. If the app gains traction, we plan to request special permissions from the 42 Network—and potentially Staff privileges—to unlock full reservation capabilities!)*
*   **🎭 Student Clubs**: Create, discover, and join campus-specific student clubs. Featuring member management and admin dashboards.
*   **👾 Gamification (Incubator - WIP)**: A unique mini-game experience currently under active development. Hatch eggs in the Incubator and grow your own "Titu" pet as you progress through your 42 journey.
*   **🌍 Multi-language Support**: Fully localized in English, Spanish, and French.
*   **🌙 Dark Mode First**: Beautiful UI tailored for both iOS and Android.
*   **📱 Responsive UI**: We are continuously tweaking the design to ensure perfect responsiveness across all mobile screen sizes and resolutions.

---

## 🛠️ Technology Stack

The project embraces a full-Dart ecosystem, sharing models and logic between the frontend and the backend.

### Frontend (Mobile App)
*   **Framework**: [Flutter](https://flutter.dev/) (Dart)
*   **State Management**: BLoC / Cubit pattern
*   **Dependency Injection**: GetIt
*   **Routing**: GoRouter
*   **Localization**: Flutter Localizations (ARB files)

### Backend (API Server)
*   **Framework**: [Serverpod](https://serverpod.dev/) (Dart)
*   **Database**: PostgreSQL
*   **Caching**: Redis
*   **Authentication**: Custom 42 Identity Provider integrated with Serverpod Auth.

---

## 🔒 Privacy & Security

We take student privacy seriously. The app is built with a "device-first" approach for sensitive data:
*   **Intra 42 Data**: All personal progress, projects, and coalition data flow directly from the 42 API to the user's device. Our backend does not store your academic records.
*   For more details, check out our [Privacy Policy](URL_PRIVACY_POLICY).

---

## 📱 Screenshots

> **Note:** Check out the app in action on the [App Store](URL_APPLE_STORE) or [Google Play](URL_GOOGLE_PLAY) for high-resolution screenshots and previews!

---

## 🤝 Contributing & Feedback

**Mi Fortitu is a community-driven project.** We highly encourage and welcome contributions from fellow 42 students! 

*   **🌐 Translations:** Want the app in your language? Help us add new translations!
*   **🗺️ Campus Mapping:** We need help mapping the cluster layouts for different 42 campuses around the world so everyone can find their peers.
*   **🐛 Feedback & Bug Reports:** Any feedback, feature requests, or bug reports are incredibly valuable to us.

If you want to collaborate or have an idea to improve the app, please don't hesitate to open an issue or reach out!

---

## 🧑‍💻 Development & Architecture Highlights

*   **Clean Architecture**: Separation of concerns across Presentation, Domain, and Data layers.
*   **Shared Protocol**: Leveraging Serverpod's generated client, ensuring 100% type safety between the backend database and the Flutter UI.
*   **Role-Based Access Control**: Built-in hierarchy distinguishing standard students, campus staff, testers, and system administrators.

---
<div align="center">
  <i>Developed with ❤️ by a 42 Student for 42 Students.</i>
</div>
