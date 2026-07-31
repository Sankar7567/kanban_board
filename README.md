# QuestBoard - Gamified Kanban & Task Tracker

**QuestBoard** is an interactive, gamified task tracker designed to make productivity fun. Built as a fully offline-capable, standalone web application, it combines the organizational power of a Kanban board with RPG mechanics like levels, experience points (XP), streaks, and achievements. 

## 🚀 Features

### 🎮 Gamification & RPG Mechanics
* **Experience Points (XP):** Earn XP for completing tasks based on their priority (Low, Medium, High).
* **Leveling System:** Watch your character rank up from "Task Novice" to "Flow State Archmage" as you accumulate XP.
* **Achievements & Badges:** Unlock visual badges by completing milestones (e.g., first quest, daily streaks, total tasks).
* **Daily Streaks:** Keep the momentum going. Earn streaks for completing tasks on consecutive days.
* **Level-Up Celebrations:** Enjoy visual and audio feedback (confetti and chimes) when you achieve a new level or badge.

### 📋 Interactive Kanban Board
* **Drag-and-Drop Columns:** Effortlessly move quests between "To Do", "In Progress", "Blocked", and "Completed".
* **Task Customization:** Add descriptions, categories (Work, Study, Personal, Health, Admin), priorities, and estimated times.
* **Recurring Quests:** Set tasks to reset automatically on a daily or weekly basis.
* **Search & Filter:** Quickly find quests using the keyboard shortcut (`/`) or filter by category.

### ⏱️ Productivity Tools
* **Built-in Pomodoro Timer:** A dedicated focus timer (default 50 minutes) integrated directly into the header to track deep-work sessions.
* **Statistics Dashboard:** Track your daily XP, weekly completion rate, blocked quests, and total completions.
* **Daily Quotes:** Stay inspired with rotating motivational quotes.

### 🛠️ Technical Capabilities
* **Offline-First:** All assets (fonts, icons, styles, and scripts) are bundled locally. No internet connection is required to use the app.
* **Local Storage:** All your quests, XP, and settings are saved securely in your browser's local storage.
* **Data Portability:** Easily **Backup** and **Restore** your progress using JSON files.
* **Dark / Light Mode:** A fully responsive glassmorphism UI that supports both dark and light modes.
* **PWA Support:** Install QuestBoard directly to your desktop or mobile home screen as a Progressive Web App.

## 🛠️ Technology Stack
QuestBoard is built using vanilla web technologies, requiring no build steps or bundlers:
- **HTML5 & Vanilla JavaScript** (Logic and State Management)
- **CSS3 & Tailwind CSS** (Styling, provided via local script)
- **Lucide Icons** (UI icons)
- **SortableJS** (Drag-and-drop functionality)
- **Canvas Confetti** (Celebration animations)
- **Web Audio API** (Procedural notification chimes)

## 📦 Getting Started

Since QuestBoard is a static, client-side application, getting started is incredibly simple:

1. Clone or download this repository to your local machine.
2. Ensure you have the `assets` folder in the same directory as `index.html`.
3. Open `index.html` in any modern web browser.
4. Start adding your quests and leveling up!

## 💾 Data Backup

Your data is stored locally in your browser. To ensure you don't lose your progress (e.g., if you clear your browser cache):
1. Click the **Backup** button in the sidebar to download your current save file (`questboard-backup.json`).
2. To load your progress on another device or browser, use the **Restore** button and upload your JSON file.

## 🤝 Contributing
Feel free to fork this project, submit pull requests, or report issues if you'd like to improve QuestBoard.
