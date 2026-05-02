<div align="center">

<!-- HEADER BANNER -->
<img src="assets/header.png" alt="Guess The Number – Car Race Edition" width="100%"/>

<br/>

# 🎯 Guess The Number — Car Race Edition

**A difficulty-driven number guessing game with animations, scoring, and a race-themed UI — built with Python & Streamlit.**

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-FF4B4B?style=for-the-badge&logo=streamlit)](https://streamlit.io/)
[![Hackathon](https://img.shields.io/badge/Hackathon-Winter_5.0-blueviolet?style=for-the-badge)](https://github.com/loisekk)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Author](https://img.shields.io/badge/Author-Yash%20Brahmankar-orange?style=for-the-badge)](https://github.com/loisekk)

> *"Guess the number. Win the race. Beat your score."*

</div>

---

## 🌟 Preview

<div align="center">
  <img src="assets/demo.gif" width="700" alt="Guess The Number – Car Race Edition Demo"/>
  <br/>
  <sub>Live gameplay — difficulty selection, hints, animation, and score reveal</sub>
</div>

---

## 📌 Overview

**Guess The Number – Car Race Edition** upgrades the classic CLI number-guessing game into a fully interactive web application using Streamlit.

Players pick a difficulty, receive hot/cold hints after each guess, and trigger a car race animation on winning — all in the browser, no installation required for end users.

Built as a hackathon submission for **Winter 5.0**, focusing on creativity, clean UI, and real game logic.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🎚 Difficulty Levels | Easy / Medium / Hard — adjusts range + attempt limit |
| 🔢 Random Generation | Fresh number each session via Python `random` |
| 💡 Smart Hints | Higher / Lower feedback after every guess |
| 🏎 Race Animation | Car progress bar triggers on correct guess |
| 🏆 Score System | Performance-based scoring (attempts remaining × multiplier) |
| 🔄 Restart Option | Reset game without refreshing the page |
| 🖥 Clean UI | Streamlit-powered, no HTML/CSS required |

---

## 🧠 How It Works

```
Select difficulty → Number generated → Enter guess → Get hint → Repeat
                                                                   ↓
                                               Win → Animation + Score 🎉
                                               Lose → Game over screen
```

**Difficulty config:**

| Level | Number Range | Max Attempts |
|---|---|---|
| Easy | 1 – 50 | 10 |
| Medium | 1 – 100 | 7 |
| Hard | 1 – 200 | 5 |

---

## 🛠 Tech Stack

| Layer | Tool | Purpose |
|---|---|---|
| Language | Python 3.x | Core game logic |
| Web UI | Streamlit | App rendering + interactivity |
| State | `st.session_state` | Persistent game state across interactions |
| Logic | `random` | Number generation |
| Animation | `time` | Frame-based race animation |

---

## 🚀 Getting Started

**Clone the repo:**

```bash
git clone https://github.com/loisekk/guess-the-number-streamlit.git
cd guess-the-number-streamlit
```

**Install dependency:**

```bash
pip install streamlit
```

**Run the app:**

```bash
streamlit run streamlit-UI.py
```

App opens at `http://localhost:8501` in your browser.

---

## 📂 Project Structure

```
guess-the-number-streamlit/
├── streamlit-UI.py      # Main app — UI, state, and game loop
├── game_logic.py        # Number generation, scoring, hint logic
├── assets/
│   ├── header.png       # Banner image
│   └── demo.gif         # Gameplay demo
└── README.md
```

---

## 🎯 Learning Outcomes

- Building stateful web apps with `st.session_state`
- Designing interactive UIs without frontend frameworks
- Structuring game logic cleanly in Python
- Implementing animation in a web context
- Shipping a complete project under hackathon time constraints

---

## 🔮 Roadmap

- [ ] Global leaderboard system
- [ ] Sound effects on win/loss
- [ ] Dark mode toggle
- [ ] Mobile-responsive layout
- [ ] Multiplayer mode (guess race)

---

## 🏆 Hackathon

> Submitted to **Winter 5.0 Hackathon** — track: creativity, usability, clean implementation.

---

## 👨‍💻 Author

**Yash Brahmankar**
B.Tech AI & ML | OIST, 2024–2028

[![GitHub](https://img.shields.io/badge/GitHub-loisekk-181717?style=flat-square&logo=github)](https://github.com/loisekk)
[![Email](https://img.shields.io/badge/Email-yashbrahmankar95@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:yashbrahmankar95@gmail.com)

---

## 📄 License

Licensed under the [MIT License](LICENSE) — free to use, modify, and distribute.

---

<div align="center">
  <sub>Built with Python · Powered by Streamlit · Submitted at Winter 5.0</sub>
</div>
