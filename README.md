# 🏋️ WorkoutPro

> Gym Planner — AI-generated full-stack web application

Workout routine builder with exercise library, set/rep tracking, muscle group heatmaps, and personal records.

**Built by [MiMo](https://100t.xiaomimimo.com/)** 🤖

---

## 📸 Screenshots

### Dashboard View
![WorkoutPro Dashboard](screenshots/project_WorkoutPro_dashboard.png)

### Full Page
![WorkoutPro Full Page](screenshots/project_WorkoutPro_full.png)

---

## ✨ Features

- Routine builder
- Exercise library
- Set/rep tracker
- Muscle heatmap
- Personal records
- Rest timer

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│                  WorkoutPro Frontend                  │
├─────────────────────────────────────────────────┤
│  ┌──────────┐  ┌──────────┐  ┌──────────────┐  │
│  │ index.html│  │ style.css │  │  script.js   │  │
│  │  (Layout) │  │ (Styling) │  │ (Logic+Data) │  │
│  └──────────┘  └──────────┘  └──────────────┘  │
│        │              │              │           │
│        └──────────────┼──────────────┘           │
│                       │                          │
│              ┌────────▼────────┐                 │
│              │   DOM Rendering  │                 │
│              │   Event Handlers │                 │
│              │   Chart Canvas   │                 │
│              └─────────────────┘                 │
└─────────────────────────────────────────────────┘
```

---

## 🚀 Quick Start

```bash
git clone https://github.com/Kania-agent/WorkoutPro.git
cd WorkoutPro
npm install
npm start
```

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Flexbox + Grid layout, responsive design
- **JavaScript** (ES6+) — DOM manipulation, Canvas API
- **Canvas API** — Data visualization charts

---

## 📄 License

MIT © Kania-agent

---

*This project was built as part of the [MiMo](https://100t.xiaomimimo.com/) developer grant program.*
