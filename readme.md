# PEPEger App – Whitepaper v1.0

## Overview

**Pepeger** is a lightweight, notification-based mobile application designed to efficiently broadcast important messages to a community, without relying on centralized infrastructure. Inspired by the simplicity and directness of old-school pagers, the app allows users to receive timely alerts, interact with links, and take action quickly – all in a minimal, distraction-free interface.

Pepeger v1.0 is currently available for **Android (API 21+, Android 5.0 Lollipop and above)** and distributed in **APK format**. A **Google Play** release is planned for wider adoption and easier updates.

---

## Key Features

- 📩 **Message Reception**  
  Receive short, actionable messages directly to your phone. Each message can contain a clickable link for immediate redirection (e.g. voting, signing, participating).

- 🔔 **Instant Notifications**  
  Get notified immediately when a new message appears or an existing one is updated. No need to check Discord or forums constantly – the info comes directly to you.

- ⏰ **Expiration System**  
  Messages can have an expiration timestamp, which ensures users only see relevant and up-to-date information.

- 🎨 **Color-Coded Priority**  
  Messages are categorized based on urgency:
  - **Red** – Critical
  - **Yellow** – Important
  - **Green** – Normal

- 🔄 **Real-Time Data Updates**  
  The application fetches data from a configurable .json source every 5 minutes, ensuring up-to-date information. Additionally, users can manually refresh the data by tapping the refresh button ⟳.

- 🔊 **Musical Surprise**  
  A small, lighthearted element awaits users within the app — a **musical Easter egg** for those curious enough to explore!

---

## Architecture & Data Handling

- 🗂️ **Dynamic Data Source**  
  Pepeger reads messages from a customizable `.json` file hosted externally. This offers flexibility and full control over message distribution. The current setup ensures **instantaneous data delivery** upon changes.

- 🔒 **Privacy-Friendly**  
  The app does not collect or store any personal data. Its purpose is purely functional — to display messages and links.

---

## Installation & Compatibility

- 📦 **APK Download**  
  Users can install the application from the following link:  
  👉 [Download APK](https://github.com/exgoust/pepeger/blob/main/pepeger-release.apk) *(link may be updated if moved elsewhere)*

- 📱 **Minimum Requirements**  
  - Android 5.0 (API 21) and above  
  - Internet connection (for message retrieval)  
  - **Important:** Battery optimization must be disabled for full background functionality

---

## Known Limitations

- 🔋 **Battery Optimization**  
  Without disabling battery optimization, Android may put the app into **Doze Mode**, delaying notifications.

- 📲 **Device Testing Needed**  
  While tested on several devices, broader testing is encouraged — especially on older models. If the app crashes or messages don’t load, feedback is appreciated.  
  👉 [Join the Community on Discord](https://discord.com/invite/6NXJt25q2J)  
  📬 Contact: **@ex.goust**

---

## Current Status & Next Steps

- ✅ **v1.0 Release:** App tested, stable, and live in APK form  
- 🧪 **Testing Phase:** Currently being tested by early users  
- 📈 **Next Steps:**
  - Google Play listing
  - iOS version (TBD)

---

## Feedback & Participation

If you’ve installed Pepeger, we’d love to know:
- Your **phone model**
- Your **Android version**
- Any **bugs** or **unexpected behavior**
- General **suggestions**

Your input will help shape the app’s future!

---

## Conclusion

Pepeger aims to provide a simple, effective way to distribute high-priority community messages. With minimal setup, instant updates, and real-time notifications, it offers a decentralized communication tool that works — fast.

Let’s make communication quicker, clearer, and more fun.

🎵 Oh, and don’t forget to listen for the musical surprise! 🎵
