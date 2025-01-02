<div align="center">

# TIDYTASK FLUTTER 🚀

### Smart to-do app with offline SQLite support via sqflite in Flutter

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/ram7767/tidytask-flutter?style=for-the-badge)

</div>

---

## ✨ Features

| Feature | Status |
|---------|--------|
| 🔐 User Authentication | ✅ |
| 💬 Real-time Updates | ✅ |
| 📦 Offline Support | ✅ |
| 🌙 Dark Mode | ✅ |
| 🔔 Push Notifications | ✅ |
| 🧪 Unit Tests | ✅ |

---

## 🏗️ Architecture

This project follows **Clean Architecture** principles with clear separation of concerns:

```
Presentation Layer   →   Domain Layer   →   Data Layer
    (UI/Views)             (UseCases)        (Repos/APIs)
```

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| Language | Dart 3.x |
| Framework | Flutter 3.x |
| State Management | Riverpod / Bloc |
| Local DB | SQLite (sqflite) / Hive |
| Remote | Firebase / REST |
| Testing | flutter_test |

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK 3.x
- Dart SDK 3.x
- Android Studio or VS Code

### Installation

```bash
# Clone the repository
git clone https://github.com/ram7767/tidytask-flutter.git
cd tidytask-flutter

# Install Flutter dependencies
flutter pub get

# Run the app
flutter run
```

---

## 📁 Project Structure

```
tidytask-flutter/
├── lib/
│   ├── main.dart
│   ├── app/              # App config & routing
│   ├── features/         # Feature modules
│   │   ├── auth/
│   │   ├── home/
│   │   └── profile/
│   ├── core/             # Shared utilities
│   │   ├── network/
│   │   ├── database/
│   │   └── utils/
│   └── shared/           # Shared widgets
├── test/
├── assets/
└── pubspec.yaml
```

---

## 🗺️ Roadmap

- [x] Core architecture setup
- [x] Authentication flow
- [x] Main feature implementation
- [x] Offline support
- [ ] iPad / tablet layout
- [ ] Localization (i18n)
- [ ] Performance optimizations
- [ ] App Store / Play Store release

---

## 🤝 Contributing

Contributions are warmly welcome!

1. Fork the repository
2. Create your branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'feat: add amazing feature'`
4. Push the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

Please follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.

---

<div align="center">

Made with ❤️ by [@ram7767](https://github.com/ram7767)

⭐ Star this repo if you found it helpful!

</div>
