# 🧠 Multiplication Mastery

An elegant, high-performance, keyboard-driven math puzzle game designed to help developers, students, and arithmetic enthusiasts build lightning-fast mental multiplication recall!

Play the live game instantly right inside your browser:  
👉 **[Click Here to Play!](https://github.com/BroMarioMethod/multiplication-mastery/)**

---

## ✨ Features

- **🎮 3 Dynamic Modes:**
  - 🟢 **Easy (6x6 Grid):** Focuses on basic single-digit tables (factors 2–7).
  - 🟠 **Difficult (11x11 Grid):** Introduces intermediate challenges (factors 2–12).
  - 🔴 **Pro (16x16 Grid):** Test your absolute limits with advanced factors (factors 2–17).
- **🔀 Smart Header Shuffling:** Enable "Shuffle Headers" to scramble row and column orientations on every restart, completely preventing muscle memory cheating.
- **⚡ Combo Score Multiplier:** Correct answers built-up consecutively fuel an active combo multiplier (up to 1.5x, 2.0x, etc.) for high-score maximisation!
- **⌨️ Keyboard-optimized Speedruns:** Complete flow is designed to be completed mouse-free. Use **Arrow keys (←, →, ↑, ↓)**, **Tab**, or **Enter** to hop across input boxes.
- **🏆 On-Device Leaderboard & Safe Login:** Tracks your top 10 historical records locally utilizing secure browser `localStorage` storage. Fully protected against XSS injection attacks.
- **🎓 Interactive Quick-Guide:** A built-in modal onboarding tutorial introduces core concepts to new visitors. Can be muted permanently.

---

## 🛠️ Tech Stack & Architecture

This is a lightweight static web application. It requires absolutely zero servers, database backend APIs, or packages to compile:
- **HTML5** Structure
- **CSS3** Grid/Flexbox Layouts (utilizing CSS variables for a customized dark-mode aesthetic theme)
- **Vanilla JavaScript (ES6+)** for procedural grid generation, dynamic mathematical checks, keyboard binding event handlers, and data sanitization.

---

## 🚀 Deployment & Local Hosting

### Play Locally
1. Clone this repository or download the source code:
   ```bash
   git clone [https://github.com/BroMarioMethod/multiplication-mastery.git](https://github.com/BroMarioMethod/multiplication-mastery.git)
