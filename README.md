<div align="center">

# 🖥️ Service Marketplace Admin Panel

**A Flutter web dashboard for managing users, service providers, chats and platform analytics for an on-demand services marketplace.**

![Flutter Web](https://img.shields.io/badge/Flutter%20Web-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)

</div>

> 🔒 **Client project — source code is private.** Details are described generically. This page summarises the product and my role as the developer.

---

## 🎯 The problem

An on-demand services marketplace connects households with vetted service providers. Behind the scenes, the operations team needs to verify providers, answer user questions, monitor activity and keep the platform trustworthy — and spreadsheets plus the database console don't scale.

## 💡 The solution

A **web-based admin panel** that gives the operations team one place to manage the marketplace: browse and moderate users, review provider portfolios, handle conversations and watch platform metrics on live charts.

---

## ✨ Key features

| Feature | What it does |
|---|---|
| 🔐 **Secure admin login** | Authenticated access with phone/OTP verification and role-protected routes. |
| 👥 **User & provider management** | Search, review, edit and moderate customers and service providers. |
| 🗂️ **Provider portfolios** | View each provider's profile, services, photos and verification details. |
| 💬 **Chat monitoring & support** | Read and respond to conversations between users and providers. |
| 📈 **Analytics dashboard** | Interactive charts for signups, activity and growth trends. |
| 📍 **Maps & location tools** | Pick and visualise service areas; geo-queries for nearby providers. |
| 🗑️ **Account & data controls** | Admin-side tools for account removal and data requests. |
| 🧭 **Responsive web UI** | Side-menu navigation, header and clean data tables built for desktop use. |

---

## 🏗️ Architecture & engineering highlights

- **Flutter Web** — a single Dart codebase delivering a fast, responsive admin dashboard.
- **Layered architecture** — `models · services · providers · views · widgets`, with services for auth, users, chat, home and graph data.
- **Provider** for state management, with separate data and UI providers.
- **go_router** for deep-linkable, guarded web routes.
- **Firebase** — Authentication, Cloud Firestore and Realtime Database for live data and chat, plus Cloud Storage for media.
- **Geo-queries** using GeoFlutterFire for nearby-provider lookups.
- **OTP flows** with SMS autofill and Twilio-based verification.
- **Charts** — Syncfusion charts for interactive analytics.

## 🧰 Tech stack

**Flutter Web · Dart · Provider · go_router · Firebase Auth · Cloud Firestore · Realtime Database · Firebase Storage · Google Maps · GeoFlutterFire · Twilio · Syncfusion Charts**

---

## 📸 Screenshots

*Screenshots available on request (client approval).*

---

## 🤝 Need an admin dashboard built?

I build production-ready admin panels and back-office tools — user management, analytics, chat and maps — to run your product from day one.

📫 **sibghat.developlogix@gmail.com** · 🌐 **[developlogix.com](https://www.developlogix.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/sibghat-ullah-baig-4a2812a1)**

<sub>Built by [Develop Logix](https://www.developlogix.com)</sub>
