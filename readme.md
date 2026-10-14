<p align="center">
  <img src="app%20pictures/app%20icon.png" alt="MedOrd Logo" width="120">
</p>

<h1 align="center">MedOrd</h1>
<p align="center">A smart pharmacy management platform connecting medicine agencies and medical stores</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white" alt="Platform">
  <img src="https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/Architecture-MVVM-14B8A6" alt="MVVM">
  <img src="https://img.shields.io/badge/Status-Active%20Development-E8A15C" alt="Status">
</p>

<p align="center">
  <a href="#about">About</a> ·
  <a href="#the-problem">Problem</a> ·
  <a href="#the-solution">Solution</a> ·
  <a href="#features">Features</a> ·
  <a href="#tech-stack">Tech Stack</a> ·
  <a href="#architecture">Architecture</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#download">Download</a>
</p>

---

## About

MedOrd is an Android application that puts medicine agencies and medical stores on one platform. Agencies manage inventory, billing, deliveries and customer communication; medical stores browse stock, place orders, track deliveries and stay current on healthcare news — all from the same system.

> This repository showcases the project. The full source is private while MedOrd is under active commercial development.

## The Problem

<img src="app%20pictures/problem.png" alt="The problem MedOrd solves" width="700">

Ordering between agencies and medical stores is still largely manual — phone calls, paper ledgers and scattered spreadsheets. Stock visibility is poor, invoicing is slow, and neither side has a reliable way to track an order from placement to delivery.

## The Solution

<img src="app%20pictures/solution.png" alt="MedOrd's solution" width="700">

MedOrd replaces that with a single connected workflow: agencies publish live stock and offers, stores order directly against it, and every order is tracked from placement through OTP-verified delivery — with billing, invoicing and reporting handled automatically along the way.

## Features

<img src="app%20pictures/features.png" alt="MedOrd feature overview" width="700">

### For Agencies
- Registration, login and premium subscription management
- Dashboard & analytics
- Stock management — add / edit / delete, batch, expiry, MRP & GST, branch-wise inventory
- Order management, order history, task assignment & completion
- Customer billing with PDF invoice generation, CSV/PDF export, auto monthly PDF reports
- Auto order-history email
- Google Maps route navigation & OTP-based order completion
- Delivery partner management
- Razorpay payment gateway
- Firebase Cloud Messaging notifications
- Health news & research hub — drug recall alerts, clinical trial updates, WHO updates, trending healthcare news
- Medicine & offer posters, notes and announcements
- Hiring management, help & support
- Firebase cloud backup & storage optimization

### For Medical Stores
- Registration & login, dashboard
- Browse agency medicines, search & check stock availability
- Place and track orders, view order history
- View medicine posters, offers, discounts, notes and announcements
- Billing & invoice download
- Auto order-history email
- Google Maps route navigation & OTP order verification
- Secure online payments
- Health news & research — drug recalls, clinical trials, WHO updates, trending healthcare news
- Help & support, Firebase Cloud Messaging notifications

### System Automation
Auto premium-expiry check & deactivation, auto-delete of old orders, monthly PDF report generation, scheduled Cloud Functions, secure Firebase Authentication, Cloud Firestore, Firebase Storage and cloud backup all run behind the scenes with no manual upkeep.

## Tech Stack

Built with **Kotlin** and **Jetpack Compose** (Material 3, MVVM architecture) on top of **Firebase** — Authentication, Cloud Firestore, Storage, Cloud Functions and Cloud Messaging — plus the **Google Maps SDK** for navigation and **Razorpay** for payments.

| Layer | Technology |
|---|---|
| UI | Kotlin, Jetpack Compose, Material 3 |
| Architecture | MVVM |
| Backend | Firebase (Auth, Firestore, Storage, Cloud Functions, FCM) |
| Maps & Navigation | Google Maps SDK |
| Payments | Razorpay |
| Tooling | Android Studio, Git & GitHub |

## Architecture

<img src="app%20pictures/architecture.png" alt="MedOrd system architecture" width="700">

## Analysis & Comparison

<img src="app%20pictures/Analysis%20%26%20compare.png" alt="Competitive analysis and comparison" width="700">

## Screenshots

<p align="center">
  <img src="app%20pictures/p1.png" width="180">
  <img src="app%20pictures/p2.png" width="180">
  <img src="app%20pictures/p3.png" width="180">
  <img src="app%20pictures/p4.png" width="180">
</p>
<p align="center">
  <img src="app%20pictures/p5.png" width="180">
  <img src="app%20pictures/p6.png" width="180">
  <img src="app%20pictures/p7.png" width="180">
  <img src="app%20pictures/p8.png" width="180">
</p>
<p align="center">
  <img src="app%20pictures/p9.png" width="180">
  <img src="app%20pictures/p10.png" width="180">
  <img src="app%20pictures/p11.png" width="180">
  <img src="app%20pictures/p12.png" width="180">
</p>
<p align="center">
  <img src="app%20pictures/p13.png" width="180">
  <img src="app%20pictures/p14.png" width="180">
  <img src="app%20pictures/p15.png" width="180">
  <img src="app%20pictures/p16.png" width="180">
</p>

## Project Structure

```text
medord
│
├── README.md
├── index.html
│
└── app pictures
    ├── app icon.png
    ├── architecture.png
    ├── features.png
    ├── problem.png
    ├── solution.png
    ├── Analysis & compare.png
    └── p1.png ... p16.png
```

## Download

Website — coming soon
APK — coming soon

## Source Code

The source code is private while MedOrd is under active commercial development. This repository exists to showcase the project's features, architecture and tech stack.

## Developer

**Lokesh Kumar**
Robotics & Automation Engineering, National Institute of Technology Kurukshetra
