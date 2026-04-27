#  Flutter Navigation & App Icon Demo

A simple Flutter application demonstrating navigation between two screens along with customization of the application icon.

---

##  Features

*  Two screens (Screen 1 & Screen 2)
*  Navigation using Flutter routes
*  Button to navigate to the second screen
*  Button to return to the first screen
*  Custom application icon support

---

##  Technologies Used

* Flutter
* Dart

---

##  Project Structure

```id="pl9x2a"
lib/
 └── main.dart
assets/
 └── icon.png   (your app icon)
```

---

##  Getting Started

Follow these steps to run the project locally:

### Prerequisites

* Install Flutter SDK
* Install Android Studio / VS Code
* Set up an emulator or connect a physical device

---

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-navigation-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-navigation-app
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

---

##  Navigation Logic

* **Screen 1**

  * Contains a button: *"Go to Second Screen"*
  * Uses `Navigator.push()` to navigate

* **Screen 2**

  * Displays a message
  * Contains a button: *"Go Back"*
  * Uses `Navigator.pop()` to return

---

##  App Icon Setup

To change the app icon, follow these steps:

### 1. Add Dependency

Add this to your `pubspec.yaml`:

```yaml
dev_dependencies:
  flutter_launcher_icons: ^0.13.1

flutter_icons:
  android: true
  ios: true
  image_path: "assets/icon.png"
```

---

### 2. Add Icon Image

* Place your icon image in the `assets/` folder
* Recommended size: **1024x1024 px**

---

### 3. Generate Icons

Run the following command:

```bash
flutter pub run flutter_launcher_icons
```

##  How It Works

* Uses `Navigator` for screen transitions
* Implements `MaterialPageRoute` for navigation
* Demonstrates basic routing in Flutter
* App icon is generated using the `flutter_launcher_icons` package

---

##  Future Improvements

* Add named routes for better navigation structure
* Add animations between screens
* Improve UI design and styling
* Add more screens and navigation options

---

##  Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

##  Author

Riya Patani

---
