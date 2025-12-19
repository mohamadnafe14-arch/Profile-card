# Profile Card - Flutter Application 🎨
![GitHub stars](https://img.shields.io/github/stars/mohamadnafe14-arch/Profile-card?style=social)
![GitHub forks](https://img.shields.io/github/forks/mohamadnafe14-arch/Profile-card?style=social)
![GitHub issues](https://img.shields.io/github/issues/mohamadnafe14-arch/Profile-card)
![GitHub pull requests](https://img.shields.io/github/issues-pr/mohamadnafe14-arch/Profile-card)
![GitHub last commit](https://img.shields.io/github/last-commit/mohamadnafe14-arch/Profile-card)
<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

A beautiful and clean personal profile card built with Flutter. Perfect for beginners learning Flutter basics!

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Contributing](#-contributing)

</div>

---

## 📱 Demo

<div align="center">
  <img src="https://github.com/mohamadnafe14-arch/Profile-card/assets/248756850/03d0f0e4-6665-4a0e-a74d-55b8806ebeec" alt="Profile Card Screenshot" width="300"/>
</div>

## ✨ Features

- 🎨 **Clean UI Design** - Modern and minimalist interface
- 📱 **Fully Responsive** - Works seamlessly on all screen sizes
- 🎭 **Custom Fonts** - Beautiful typography with custom font integration
- 🌈 **Material Design** - Following Google's Material Design guidelines
- 🚀 **Cross-Platform** - Runs on Android, iOS, Web, Windows, Linux, and macOS
- 📦 **Well Structured** - Clean and organized code architecture
- 🔰 **Beginner Friendly** - Perfect for learning Flutter basics

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Flutter SDK** (3.0 or higher) - [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Dart SDK** (included with Flutter)
- **Code Editor** - [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio)
- **Git** - [Download Git](https://git-scm.com/downloads)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mohamadnafe14-arch/Profile-card.git
   ```

2. **Navigate to project directory**
   ```bash
   cd Profile-card
   ```

3. **Install dependencies**
   ```bash
   flutter pub get
   ```

4. **Run the app**
   ```bash
   flutter run
   ```

### Platform-Specific Setup

#### For Android 📱
```bash
flutter run -d android
```

#### For iOS 🍎
```bash
flutter run -d ios
```

#### For Web 🌐
```bash
flutter run -d chrome
```

#### For Desktop 💻
```bash
# Windows
flutter run -d windows

# macOS
flutter run -d macos

# Linux
flutter run -d linux
```

## 📂 Project Structure

```
Profile-card/
│
├── android/              # Android-specific files
├── ios/                  # iOS-specific files
├── lib/                  # Main application code
│   └── main.dart        # App entry point
│
├── fonts/               # Custom fonts
│   └── [font files]
│
├── images/              # Images and icons
│   └── [image files]
│
├── web/                 # Web platform files
├── windows/             # Windows platform files
├── linux/               # Linux platform files
├── macos/               # macOS platform files
│
├── .gitignore          # Git ignore rules
├── pubspec.yaml        # Project dependencies
└── README.md           # Project documentation
```

## 🛠️ Built With

| Technology | Description |
|-----------|-------------|
| ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) | UI Framework |
| ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white) | Programming Language |
| ![Material](https://img.shields.io/badge/Material_Design-757575?style=flat&logo=material-design&logoColor=white) | Design System |

## 📚 What You'll Learn

This project covers essential Flutter concepts:

### Widgets & Layout
- ✅ `MaterialApp` - App structure
- ✅ `Scaffold` - Page layout
- ✅ `Container` - Styling and positioning
- ✅ `Column` & `Row` - Vertical and horizontal layouts
- ✅ `Text` - Text display and styling
- ✅ `Image` - Image rendering
- ✅ `Card` - Material card widget
- ✅ `CircleAvatar` - Circular images

### Styling
- ✅ Custom fonts integration
- ✅ Color schemes
- ✅ Text styling
- ✅ Padding and margins
- ✅ BoxDecoration

### Assets Management
- ✅ Adding custom fonts
- ✅ Integrating images
- ✅ Configuring `pubspec.yaml`

## 🎯 Learning Path

Perfect for developers who want to:
1. Start their Flutter journey
2. Understand basic widgets
3. Learn layout composition
4. Practice UI design
5. Build their first mobile app

## 🔧 Customization Guide

Want to make it yours? Here's how:

### 1. Update Personal Information
Edit `lib/main.dart`:
```dart
Text(
  'Your Name',
  style: TextStyle(fontSize: 40.0, color: Colors.white),
),
Text(
  'Your Job Title',
  style: TextStyle(fontSize: 20.0, color: Colors.white),
),
```

### 2. Change Profile Picture
Replace the image in `images/` folder with your photo and update:
```dart
CircleAvatar(
  backgroundImage: AssetImage('images/your-photo.jpg'),
),
```

### 3. Customize Colors
Modify the color scheme:
```dart
backgroundColor: Colors.teal, // Change to your preferred color
```

### 4. Add Custom Font
1. Add font files to `fonts/` directory
2. Update `pubspec.yaml`:
```yaml
fonts:
  - family: YourFont
    fonts:
      - asset: fonts/YourFont-Regular.ttf
```

## 📖 Useful Resources

- 📘 [Flutter Official Documentation](https://docs.flutter.dev/)
- 🎓 [Dart Language Tour](https://dart.dev/guides/language/language-tour)
- 🎨 [Flutter Widget Catalog](https://docs.flutter.dev/development/ui/widgets)
- 📚 [Flutter Cookbook](https://docs.flutter.dev/cookbook)
- 💡 [Flutter Community](https://flutter.dev/community)
- 🎥 [Flutter YouTube Channel](https://www.youtube.com/flutterdev)

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create. Any contributions you make are **greatly appreciated**!

### How to Contribute

1. **Fork** the Project
2. **Create** your Feature Branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit** your Changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push** to the Branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open** a Pull Request

### Contribution Ideas
- 🎨 Add new themes
- 🌐 Add internationalization (i18n)
- ✨ Add animations
- 📱 Improve responsive design
- 📝 Improve documentation
- 🐛 Fix bugs

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? Please open an [issue](https://github.com/mohamadnafe14-arch/Profile-card/issues).

## 📝 License

This project is licensed under the MIT License - see the [LICENSE]([LICENSE](https://github.com/mohamadnafe14-arch/Profile-card/blob/main/License)) file for details.

## 👨‍💻 Author

**Mohamad Nafe**

- GitHub: [@mohamadnafe14-arch](https://github.com/mohamadnafe14-arch)
- Project Link: [https://github.com/mohamadnafe14-arch/Profile-card](https://github.com/mohamadnafe14-arch/Profile-card)

## 🌟 Show Your Support

If this project helped you learn Flutter or you found it useful, please consider giving it a ⭐!

<div align="center">

### Made with ❤️ and Flutter

[![Star on GitHub](https://img.shields.io/github/stars/mohamadnafe14-arch/Profile-card?style=social)](https://github.com/mohamadnafe14-arch/Profile-card/stargazers)
[![Fork on GitHub](https://img.shields.io/github/forks/mohamadnafe14-arch/Profile-card?style=social)](https://github.com/mohamadnafe14-arch/Profile-card/network/members)

</div>

---

<div align="center">
  <sub>Built as part of Flutter Basics Learning Series</sub>
</div>
