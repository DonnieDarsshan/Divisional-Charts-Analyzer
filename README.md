# Divisional Charts Analyzer

A **pure client-side astrology analysis tool** built with **HTML, CSS, and Vanilla JavaScript**.  
This project focuses on **Divisional Charts, South Indian Kundali visualization, KP / Vedic systems, pivot-based house logic, and planetary counters** — all without any backend or external libraries.

---
## ✨ Features
- Live Demo
- https://donniedarsshan.github.io/Divisional-Charts-Analyzer/



## ✨ Features

### 🔢 Precision Input System
- Degree / Minute / Second input with:
  - Arrow key increment & decrement
  - Auto-jump logic
  - Separate **Ignore Minutes** and **Ignore Seconds** toggles
- Strict numeric validation
- Supports **alphanumeric names (max 20 chars)**

### 🧭 Chart Logic
- **South Indian Kundali** with accurate sign placement
- Planet sorting:
  - Aries → Virgo (ascending)
  - Libra → Pisces (descending)
- House numbering based on selected pivot

### 🔁 Calculation Modes
- **KP System (0° Bhava)**
- **Vedic System (±15° Bhava)**
- **Sign-to-Sign (degree-less)**
- Mode exclusivity enforced automatically

### 🔄 Pivot-Based Analysis
- Pivot can be **Lagna or any planet**
- Global offset logic applied consistently across:
  - Kundali rendering
  - Forward & Retro house counters

### 📊 Counter Table
- Forward house count
- Retro (reverse) house count
- Order dynamically rotates based on pivot planet

### 💾 Data Handling
- Save chart as JSON
- Load chart from JSON
- Fully offline — no server, no storage dependency

### 🎨 UI Theme
- **Emerald Matrix × Egyptian Temple**
- GPU-friendly gradients
- Responsive layout
- Zero frameworks

---

## 🧩 Project Structure


> This is a **single-file application by design**.

---

## 🚀 How to Run

1. Download or clone the repository
2. Open `index.html` in **any modern browser**
3. No installation, no dependencies

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom theming, no frameworks)
- Vanilla JavaScript (ES6+)

---

## 📌 Notes

- 100% client-side
- Works offline
- Designed for astrology research & experimentation
- No external APIs or libraries used

---

## 📄 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute it.

---

## 👤 Author

Created & maintained by **[Your Name]**
