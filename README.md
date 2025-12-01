# Chronix ⏱️

**A modern, cross-platform productivity companion powered by Flutter**

![Flutter](https://img.shields.io/badge/Flutter-3.8+-02569B?style=flat\&logo=flutter\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.8+-0175C2?style=flat\&logo=dart\&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)
![Platforms](https://img.shields.io/badge/Platforms-Android%20|%20iOS%20|%20Web%20|%20Windows%20|%20macOS%20|%20Linux-blue)

---

## 📌 Overview

Chronix delivers a seamless and consistent experience across **mobile**, **desktop**, and **web** using a single, optimized Flutter codebase. Designed for performance, polished UI, and straightforward maintainability.

---

## ✨ Key Features

* 🌍 **Runs Everywhere** — Android, iOS, Web, Windows, macOS & Linux
* 🎯 **Clean Architecture** — Easy to scale and maintain
* 🎨 **Beautiful UI** — Adaptive Material Design visuals
* ⚡ **Fast & Fluid** — Hardware-accelerated 60fps animations
* 🔄 **Hot Reload Ready** — Iterate faster during development

---

## 🚀 Getting Started

### Requirements

| Platform    | Tools                            |
| ----------- | -------------------------------- |
| Android     | Android Studio + SDK             |
| iOS / macOS | Xcode on macOS                   |
| Windows     | Visual Studio w/ C++ build tools |
| Linux       | GTK development libraries        |
| Web         | Any modern browser               |

Install Flutter here → [https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)

---

### Installation

```bash
# Clone the project
git clone https://github.com/PranjalBasak/Chronix.git
cd Chronix

# Install dependencies
flutter pub get

# Run on default device
flutter run
```

Run on a specific platform:

```bash
flutter run -d chrome
flutter run -d windows
flutter run -d macos
flutter run -d linux
```

---

## 📁 Project Structure

```
chronix/
├── lib/
│   └── main.dart           # Entry point
├── android/                # Android configs
├── ios/                    # iOS configs
├── linux/                  # Linux configs
├── macos/                  # macOS configs
├── windows/                # Windows configs
├── web/                    # Web configs
├── pubspec.yaml            # Dependencies & metadata
└── README.md
```

---

## 🔨 Production Build Commands

```bash
flutter build apk --release       # Android
flutter build ipa --release       # iOS
flutter build web --release       # Web
flutter build windows --release   # Windows
flutter build macos --release     # macOS
flutter build linux --release     # Linux
```

---

## 🧪 Testing

```bash
# Run all tests
flutter test

# With coverage report
flutter test --coverage
```

---

## 🤝 Contributions

Pull Requests are highly appreciated!

1. Fork this repo
2. Create a feature branch → `git checkout -b feature/MyFeature`
3. Commit → `git commit -m "Add MyFeature"`
4. Push → `git push origin feature/MyFeature`
5. Open a PR 🚀

---

## 📄 License

This project is released under the **MIT License** — see the [LICENSE](LICENSE) file.

---

## 👤 Author

**Pranjal Basak**
GitHub: [https://github.com/PranjalBasak](https://github.com/PranjalBasak)

---

<p align="center">Made with ❤️ & Flutter</p>
