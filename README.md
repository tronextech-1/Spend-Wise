💰 Spend Wise - Expense Manager

A personal expense manager mobile application built with Apache Cordova and React to help you track your finances with ease.
The app is fully offline-capable, securely storing all data locally on your device.

Developed by: Ubaid Ur Rehman
 at TRONEX

✨ Features

Transaction Management: Add, edit, and delete income (In) and expense (Out) transactions.

Dashboard: Get a clear summary of your total income, expenses, and current balance.

Offline First: Works entirely offline using IndexedDB — no internet required.

Multi-language Support: Switch between English and Urdu.

Light & Dark Themes: Choose a theme that suits your style.

Voice Input: Add transactions using your voice (powered by cordova-plugin-speechrecognition).

Advanced Filtering & Sorting: Find transactions by type, description, or amount — and sort by date or value.

Image-Based Reports: Generate and share weekly, monthly, or all-time reports as images.

Secure & Private: 100% offline — no data ever leaves your device.

User Profile: Set your personal or organization name for customized reports.

In-App Calculator: Perform quick calculations without switching apps.

🛠️ Tech Stack
Layer	Technology
Framework	Apache Cordova
Frontend	React (via UMD), HTML5, CSS3
Storage	IndexedDB
Report Generation	html2canvas


📂 Folder Structure
SpendWiseApp/
├── config.xml                 
├── resources/                 
│   └── android/
│       ├── icon/
│       │   ├── drawable-hdpi-icon.png
│       │   ├── drawable-mdpi-icon.png
│       │   └── ... (other densities)
│       └── splash/
│           ├── drawable-port-hdpi-screen.png
│           └── ... (other densities)
└── www/                     
    └── index.html           


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
