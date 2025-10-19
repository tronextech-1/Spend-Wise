💰 Spend Wise - Expense Manager

A personal expense manager mobile application built with Apache Cordova and React to help you track your finances with ease.
The app is fully offline-capable, securely storing all data locally on your device.

Developed by: Ubaid Ur Rehman
 at TRONEX


🚀 How to Build the APK (for Android)
🧩 Prerequisites

Make sure you have the following installed:

Node.js and npm

Java Development Kit (JDK)

Android Studio
 (for SDK tools)

Apache Cordova CLI

🧱 Install Cordova Globally

 npm install -g cordova

⚙️ Build Steps
1. Clone the Repository
git clone https://github.com/tronextech-1/Spend-Wise.git

  cd SpendWiseApp

2. Add the Android Platform
cordova platform add android

3. (Optional) Check Requirements
cordova requirements android

4. Build the Debug APK
cordova build android


📍 Debug APK Location:

platforms/android/app/build/outputs/apk/debug/app-debug.apk


🔌 Cordova Plugins Used.
Plugin	Purpose
cordova-plugin-statusbar	Controls the device status bar
cordova-plugin-splashscreen	Displays and hides the splash screen
cordova-plugin-network-information	Detects online/offline status
cordova-plugin-speechrecognition	Enables voice-to-text input
cordova-plugin-file	Handles file access for sharing reports
cordova-plugin-x-socialsharing	Enables sharing of image reports
cordova-plugin-device	Provides basic device information

🧭 Roadmap (Planned Features)

 Export reports as PDF

 Cloud backup & sync (optional)

 Budget planning with alerts

 PWA web version

🧑‍💻 Developer

Ubaid Ur Rehman
🔹 Developer at TRONEX
🔹 GitHub Profile

📜 License

This project is licensed under the MIT License — feel free to use, modify, and distribute it.
