# HabitTracker

A tiny, no-backend habit tracker. Add habits, log a short comment each day, and see your progress bar fill up.

> Empty state: **“No habits yet — add your first one to start tracking progress.”**

## How it works
- 100% client-side (HTML/CSS/JS).
- Data is stored in `localStorage` under the key `HABBIT_KEY`.
- Your data persists in the same browser/device. Clearing site data or using another browser will reset it.

## Features
- Multiple habits with icons.
- Per-day comments.
- Progress calculation toward a target number of days.
- Simple popup to add a new habit.

## Quick start

**Option A — clone this repo**
```
git clone https://github.com/Aertyr98/HabitTracker.git
cd HabitTracker
```
Option B — fork & clone your fork (if you plan to push changes)

Click Fork on GitHub.
Then:
```
git clone https://github.com/<your-username>/HabitTracker.git
cd HabitTracker
```

Open index.html in a browser (or run a static server).
