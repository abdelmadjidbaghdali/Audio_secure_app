# 🔐 Audio_secure_app

> A secure biometric-gated audio player built with Flutter & Firebase.  
> Stream, protect, and personalize your listening experience.

<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,firebase,androidstudio,vscode,git,github" />
</p>

---

## 📖 About

Audio_secure_app is a secure mobile audio player built with **Flutter** and **Firebase**. It combines biometric authentication with cloud synchronization to provide a safe and personalized listening experience. Users can stream audio, manage favorites across devices, and monitor their listening habits through detailed statistics—all within a modern dark-themed interface.

---

## ✨ Features

| Feature | Description |
|----------|-------------|
| 🔐 **Biometric Gate** | Fingerprint authentication on launch. Redirects users to system settings if no fingerprint is enrolled. Plays a success sound after successful authentication. |
| 👤 **Firebase Auth** | Sign up, login, password reset, and age validation (13+). Stores user information including name, surname, and birthdate. |
| 📊 **Stats Dashboard** | Displays total listening time, daily listening histogram, top tracks, and monthly listening goal progress. |
| 🎵 **Audio Player** | Background playback, dynamic playlists from an external API, play, pause, and repeat support. |
| ❤️ **Cloud Favorites** | Favorites are synchronized with Cloud Firestore. Removing a favorite requires biometric confirmation. |

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=flutter,dart,firebase" />
</p>

| Category | Technology |
|----------|------------|
| **Framework** | Flutter 3.x |
| **Language** | Dart |
| **Backend** | Firebase Authentication & Cloud Firestore |
| **Biometrics** | `local_auth` |
| **Audio** | `just_audio`, `audio_service` |
| **Charts** | `fl_chart` |
| **Local Storage** | `shared_preferences` |
| **API** | Quran Audio API |

---

## 📂 Project Structure

```text
lib/
├── core/             # theme, constants, utils
├── features/
│   ├── auth/         # biometric + firebase auth
│   ├── player/       # audio playback, playlist
│   ├── stats/        # dashboard, charts
│   └── favorites/    # cloud-synced favorites
├── models/           # data models
├── services/         # firebase, audio API, biometrics
└── main.dart
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Audio_secure_app.git
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Connect Firebase

Add the following files to your project:

- `google-services.json` (Android)
- `GoogleService-Info.plist` (iOS)

Then enable the following Firebase services:

- Firebase Authentication
- Cloud Firestore

### 4. Run the application

```bash
flutter run
```

---

## 📋 Requirements

- Flutter SDK 3.0 or later
- Android 6.0+ / iOS 11+
- Physical device or emulator with fingerprint capability

---

## 📸 Screenshots

> Add screenshots of your application here.

| Home | Player | Statistics | Favorites |
|------|---------|------------|------------|
| ![](screenshots/home.png) | ![](screenshots/player.png) | ![](screenshots/stats.png) | ![](screenshots/favorites.png) |

---

## 📄 License

This project is intended for educational purposes.
