# 🤖 AI Chatbot App — Flutter

A smart and intuitive chat application powered by **Gemini AI**, built using **Flutter**. The app allows users to chat with an AI assistant, browse past conversations, and enjoy a seamless chat experience with smooth scrolling and a modern UI.

---

## 📸 App Screenshot

![Screenshot](assets/screenshots/app_demo.png)

---

## 🌟 Overview

This project demonstrates how to integrate **Google’s Generative AI (Gemini)** with a Flutter-based chat interface.
The chatbot responds in real time, stores your conversations locally, and provides a smooth user experience similar to modern messaging apps.

Whether you're learning Flutter, building your first AI app, or experimenting with conversational UIs — this project is a great starting point.

---

## 🚀 Features

### 💬 Interactive Chat Interface

* Real-time two-way communication with the **Gemini AI chatbot**
* Auto-scrolling to the newest message
* Markdown-supported responses for rich content

### 🕒 Chat History

* View all previous conversations
* Locally saved using **Hive** for fast and offline-ready storage

### 📁 Local Storage Support

* Stores messages and optional app data
* Efficient, secure, and fast NoSQL storage with **hive** and **hive_flutter**

### 🖼 Image Support

* Pick images from gallery or camera using **image_picker**
* Useful for future AI vision integration

### ⚙️ Clean State Management

* Built using **Provider**, keeping the app scalable and easy to maintain

---

## 📦 Dependencies

This app uses the following Flutter packages:

* `flutter`
* `google_generative_ai` — Gemini AI integration
* `flutter_markdown` — Render formatted markdown content
* `provider` — State management
* `hive` & `hive_flutter` — Local storage
* `image_picker` — Selecting images
* `path_provider` — File system access
* `cupertino_icons` — iOS-style icons
* `flutter_spinkit` — Loading animations
* `flutter_dotenv` — Load API keys from `.env`
* `uuid` — Generate unique message IDs

---

## 🛠️ Getting Started

Follow the steps below to run the project on your device.

### 1️⃣ Install Flutter

Make sure Flutter & Dart are installed:
[https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)

### 2️⃣ Clone or Download the Project

```
git clone <your-repository-url>
```

### 3️⃣ Get Your Gemini API Key

Visit **Google AI for Developers**:
[https://ai.google.dev/](https://ai.google.dev/)

Create a `.env` file in the project root:

```
API_KEY=YOUR_GEMINI_API_KEY
```

### 4️⃣ Install Dependencies

Navigate to the project folder:

```
flutter pub get
```

### 5️⃣ Run the App

```
flutter run
```

---

## 🎯 Usage Guide

Once inside the app, you can:

* 📜 **View chat history** stored locally
* 💬 **Start a new chat** with Gemini
* 🧑 **Access your profile** or settings
* ⚡ Enjoy real-time responses and smooth navigation

The UI is designed to feel familiar and responsive, making it easy for anyone to interact with the AI system.

---

## 🤝 Contributing

We welcome contributions!
If you have ideas, improvements, or bug fixes:

1. Fork the repo
2. Create a new branch
3. Commit your changes
4. Submit a pull request

Your contributions help make the project better for everyone.

