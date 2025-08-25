Mobile Development Setup – Expo Go
📌 Objective

Mobile development typically requires more resources than web development. To simplify the process, we will be using the Expo Framework for React Native. This framework allows you to test applications efficiently without needing multiple costly device emulators.

This README documents the setup process for Expo Go and any challenges faced during installation.

✅ Prerequisites

Before starting, ensure you already have:

Node.js LTS (recommended version) installed → Download Node.js

Visual Studio Code (VS Code) installed → Download VS Code

macOS, Linux, or Windows operating system

A physical device (Android or iOS) to test your app

🚀 Why Expo Go?

Testing on emulators is often resource-heavy and can be limited by hardware.

Mobile ecosystems evolve rapidly (e.g., iPhone 7 → iPhone 16 Pro Max, many Android devices).

Expo Go provides a cost-effective, lightweight, and seamless way to test apps directly on your physical device.

Supports both iOS and Android without needing extra configurations.

📱 Installation Steps

Visit the official Expo Go page → https://expo.dev/go

Select the latest SDK version.

Install Expo Go on your device:

Android → Google Play Store

iOS → Apple App Store

Open the Expo Go app on your device.

Create a new account or log in with your existing Expo account.

🧪 Testing Setup

After installation, verify everything is working:

Run a simple Expo project on your machine:

npx create-expo-app my-first-app
cd my-first-app
npx expo start


A QR code will be generated in your terminal.

Open the Expo Go app on your phone and scan the QR code.

Your app should load on your device. 🎉

📝 Documenting Setup Challenges

If you faced any issues, note them here for future troubleshooting:

Example: “Faced issue with Expo Go login – solved by clearing app cache.”

Example: “Node.js version mismatch – updated to LTS (v18.x).”