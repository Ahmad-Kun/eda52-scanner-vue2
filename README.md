# EDA52 Scanner Demo (Vue 2 + Capacitor)

![Vue Version](https://img.shields.io/badge/Vue-2.x-brightgreen)
![Capacitor](https://img.shields.io/badge/Capacitor-Enabled-blue)
![Status](https://img.shields.io/badge/Status-Demo-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A **simple interactive demo** for integrating **Honeywell EDA52** barcode scanning with **Vue 2** using **Capacitor** for native Android support.  
Also includes a quick guide for **ngrok** live preview.  

---

##  Table of Contents
1. [Features](#-features)
2. [Requirements](#-requirements)
3. [Installation](#-installation)
4. [Capacitor Setup](#-capacitor-setup)
5. [Run & Live Preview](#-run--live-preview)
6. [Notes](#-notes)
7. [License](#-license)

---

## ✨ Features
✅ Built with **Vue 2**  
✅ Native Android integration with **Capacitor**  
✅ Optimized for **Honeywell EDA52** scanning  
✅ Temporary live preview via **ngrok**  

---

##  Requirements
- **Node.js** ≥ 14  
- **npm** or **yarn**  
- **Android Studio** (for building to device)  
- **ngrok**  

---

## 📦 Installation

**1️⃣ Clone the repo**
```bash
git clone https://github.com/yourusername/eda52-scanner-vue2.git
cd eda52-scanner-vue2
```
**2️⃣ Install dependencies**
```bash
npm install
```

---

## ⚡ Capacitor Setup
**1. Install Capacitor**
```bash
npm install @capacitor/core @capacitor/cli
```
**2. Initialize Capacitor**
```bash
npx cap init
```
> App Name: EDA52 Scanner
> App ID: com.example.eda52scanner

**3. Add Android Platform**
```bash
npx cap add android
```
**4. Open in Android Studio**
```bash
npx cap open android
```
Build and run directly on your EDA52 device 🚀

---

## ▶ Run & Live Preview
**Run in development mode**
```bash
npm run serve
```
**Live preview with ngrok**
```bash
# Install ngrok globally
npm install -g ngrok

# Run ngrok on port 8080
ngrok http 8080 or ngrok http 8080 --host-header=rewrite
```
 You’ll get a public URL → Open it on your EDA52 or share it temporarily.

---

## 📝 Notes
- This is for demo purposes only — not production-ready.
- Ngrok requires an account for extended sessions.
- Ensure EDA52 has internet access for ngrok preview.

---

## 📱 Preview
https://github.com/user-attachments/assets/5451debf-0fb9-453c-8486-70646baca835

---

## 📜 License
This project is licensed under the MIT License.
