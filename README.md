# ⚡ Daily Flow Planner

**A beautifully designed daily planner built for the way ADHD brains actually work.**

No app to install. No subscription. No iPad required. Just open the file in any browser and start planning.

---

## ✨ Features

### Daily Planning
- **Three-section daily flow** — Morning check-in → Now (tasks & focus) → Evening reflection
- **Energy & mood tracker** — Log how you're showing up each day
- **One intention** — Set a single, achievable focus for the day
- **Brain Dump** — Get everything out of your head, no judgment
- **Big 3 Tasks** — Only three tasks per day, with priority levels (Must / Should / Could), time estimates, and micro-steps
- **Time Blocks** — Colour-coded visual schedule with a live "NOW" indicator
- **Habits Today** — Quick check-in for your daily habits
- **Focus Timer** — Pomodoro-style timer with custom durations and session tracking
- **Dopamine Menu** — Personalised reward system for after each focus session
- **Win Wall** — Celebrate every win, no matter how small
- **Evening Reflection** — Three gentle questions to close the day

### Weekly & Monthly Planning
- **Weekly view** — Plan up to 8 weeks ahead, see task completion badges per day, habit dots per column
- **Monthly view** — Calendar with energy colour-coded dots, habit completion indicators, and monthly goal
- **Cross-panel intelligence** — Weekly tasks surface as suggestions in your daily view

### Habit Tracker
- Track up to 10 daily habits
- Monthly completion grid with streak counter
- Milestone celebrations at 7, 14, 30, and 100 days
- Custom emoji and 10 colour choices per habit

### Smart Features
- **Quick Capture** — Floating button to dump thoughts into Brain Dump instantly from any tab
- **Rescue Mode** — Three-question reset for rough days
- **Weekly Insights** — Monday morning recap of last week's stats
- **Mood & Energy Analysis** — Patterns by day of week, correlations with productivity
- **Backup & Restore** — Export all data as JSON, import to restore or switch devices
- **Auto-backup reminder** — Notified if you haven't backed up in 7+ days
- **History** — Browse any past day with full detail

### Design
- **Golden Hour** light theme — warm ivory with rich accent colours
- **Cosmic** dark theme — deep space background with neon glow effects
- **Fully responsive** — two-column desktop layout, mobile-optimised single column
- **Beautiful print view** — designed A4/Letter layout with section colours, visual checkboxes, and schedule grid

---

## 🚀 How to Use

1. Download `Daily_Flow_Planner.html`
2. Open it in any browser — Chrome, Firefox, Safari, Edge
3. Your data saves automatically in your browser's local storage
4. **Export your data regularly** using the 💾 button to protect against browser cache clearing

### Adding to your phone home screen

**iPhone (Safari):** Open the file → tap Share → "Add to Home Screen"  
**Android (Chrome):** Open the file → tap ⋮ menu → "Add to Home Screen"

The planner icon will appear on your home screen like a native app.

### Backing up your data

Tap the 💾 icon in the header at any time to export a `.json` backup file. Store it in iCloud, Google Drive, or anywhere you like. To restore, tap 📂 Import and select your backup file.

---

## 🗂 Files

| File | Description |
|------|-------------|
| `Daily_Flow_Planner.html` | Clean production version — blank on open, ready for customers |
| `Daily_Flow_Planner_DEMO.html` | Demo version with pre-filled data for screenshots and previews |

---

## 🛠 Technical Details

- **Single HTML file** — no dependencies, no build process, no server required
- **Works offline** — once downloaded, no internet connection needed
- **localStorage** — all data stored locally in the user's browser
- **Compatible** with Chrome, Firefox, Safari, Edge on Windows, Mac, Linux, iOS, Android, Chromebook
- **No iPad or annotation app required** — works on every device with a browser

---

## 📦 What's Stored

All data is stored under the `adhd-flow-v3` localStorage prefix:

- `adhd-flow-v3-YYYY-MM-DD` — daily entries (energy, mood, tasks, wins, reflection)
- `adhd-flow-v3-wplan-{monday}` — weekly plans
- `adhd-flow-v3-mplan-{YYYY-MM}` — monthly plans
- `adhd-flow-v3-habits` — habit definitions and all completion history
- `adhd-flow-v3-global` — theme preference
- `adhd-flow-v3-last-export` — last backup date

---

## 📄 License

© DreamsToDone. All rights reserved.

This product is sold for personal use only. Redistribution, resale, or modification for commercial purposes is not permitted without written permission.

---

*Made with ❤️ for brilliant, messy minds.*
