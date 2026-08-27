<!-- Header Banner & Title -->
<div align="center">

# 🎮 Hangman Game (Word Guessing Challenge)

**A sleek, responsive, and interactive vanilla JavaScript Hangman web game featuring animated step-by-step visual feedback and dynamic state handling.**

<br />

[![Live Preview](https://img.shields.io/badge/Live_Demo-Online-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Developer_Portfolio-V7KEYSTUDIO-black?style=for-the-badge&logo=safari&logoColor=white)](https://portfolio.v7keystudio.workers.dev)
[![GitHub](https://img.shields.io/badge/GitHub-v7keystudio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/v7keystudio)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#license)

<br />

<!-- Project Preview Screenshot -->
<p align="center">
  <img src="Preview.png" alt="Hangman Game UI Preview" width="850px" style="border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);" />
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-gameplay-rules">Gameplay</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-project-architecture">Architecture</a> •
  <a href="#-getting-started">Installation</a> •
  <a href="#-customization">Customization</a> •
  <a href="#-license">License</a>
</p>

---

</div>

## 📌 Overview

**Hangman Game** is an engaging browser-based word puzzle where players guess hidden fruit names letter by letter within a limited number of allowed mistakes. 

Built completely from scratch using clean **semantic HTML5, modern CSS3, and pure Vanilla JavaScript (ES6+)**, it delivers smooth interactions without requiring heavy external frameworks or dependencies.

---

## ✨ Key Features

* 🎯 **Dynamic Word Spotlight:** Automatically adapts to variable word lengths, revealing correctly guessed letters in real-time.
* ⌨️ **Interactive Virtual Keyboard:** Auto-generated on-screen alphabet pad with active state disabling to prevent duplicate guesses.
* 🎨 **CSS Vector Hangman Visualizer:** Step-by-step CSS-drawn hangman components (Base, Pillar, Face, Torso, Hands, Legs) that progressively appear upon incorrect guesses.
* 📊 **Real-time Counter:** Clear mistake counter displaying `Wrong Guesses: X of Max`.
* 🏆 **Win/Loss Modal Overlay:** High-impact result popup showing outcome state along with the revealed solution word.
* 🔄 **Seamless Game Resets:** Instant restart triggers (`Reset` and `New Game`) with automatic state cleanup.
* 📱 **Fully Responsive Design:** Fluid layouts optimized for mobile touchscreens, tablets, and desktop resolutions.

---

## 🕹️ Gameplay Rules

| Stage | Action / Event | Result |
| :--- | :--- | :--- |
| **1. Choose a Letter** | Click any alphabet key on the visual keyboard | The key is disabled to prevent duplicate input. |
| **2. Correct Guess** | Letter exists in the target word | All instances of the letter are revealed on the spotlight bar. |
| **3. Incorrect Guess** | Letter is not in the target word | Mistake counter increments & next hangman part is rendered. |
| **4. Victory Condition** | All letters correctly guessed before max errors | **"You Win!"** modal pops up with replay option. |
| **5. Defeat Condition** | Mistake limit reached | Hangman is fully drawn and **"Game Over"** modal reveals the answer. |

---

## 🛠 Tech Stack

<div align="left">

| Technology | Usage |
| :--- | :--- |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="18" height="18" /> **HTML5** | Semantic DOM structure and accessible modal elements |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="18" height="18" /> **CSS3** | Flexbox/Grid layouts, custom UI states, CSS vector Hangman styling |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="18" height="18" /> **JavaScript (ES6+)** | Dynamic keyboard rendering, word arrays, event listeners, game state logic |

</div>

---

## 📁 Project Architecture

```bash
DJ-V7KEY/Hangman-Game/
│
├── index.html          # Core HTML markup & modal dialogs
├── Hangman.css         # Styling, CSS Hangman vector parts, responsive media queries
├── Hangman.js          # Word repository, keyboard generator, score & game loop
├── Preview.png         # High-resolution project preview banner
└── README.md           # Comprehensive project documentation
```

---

## 🚀 Getting Started

### Prerequisites
All you need is a modern web browser (Google Chrome, Firefox, Safari, Edge, Brave).

### 1. Clone the Repository
```bash
git clone https://github.com/v7keystudio/Hangman-Game.git
cd Hangman-Game
```

### 2. Run Locally
Simply open `index.html` in your default browser:

* **Direct Open:** Double-click on `index.html` in your file explorer.
* **Or via Python Local Server:**
  ```bash
  python3 -m http.server 8000
  ```
  Then open `http://localhost:8000` in your web browser.

---

## ⚙️ Customization

Want to expand the dictionary or change the categories?

1. Open `Hangman.js` in your code editor.
2. Locate the word bank array:
   ```javascript
   const wordList = ["APPLE", "BANANA", "MANGO", "ORANGE", "PINEAPPLE", "STRAWBERRY"];
   ```
3. Add your custom list of words or categories and save!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and distribute for personal and commercial projects.

---

<div align="center">

## 👨‍💻 Developed & Maintained by

### **V7KEY STUDIO**

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio.v7keystudio.workers.dev-111111?style=flat-square&logo=cloudflare&logoColor=orange)](https://portfolio.v7keystudio.workers.dev)
[![GitHub](https://img.shields.io/badge/GitHub-v7keystudio-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/v7keystudio)

<sub>Crafted with passion for interactive web applications and elegant UI design.</sub>

</div>
