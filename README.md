# Habit Tracker

> Build streaks and stay consistent — a single-file habit tracker with a GitHub-style contribution heatmap. No backend, no account, no AI. Just vanilla JS and localStorage.

## Live Demo
https://nzjulien.github.io/habit-tracker

## Features
- Add unlimited habits with emoji icon + custom color
- One-tap daily check-in per habit
- Automatic current streak + best streak calculation
- Per-habit 14-day mini heatmap
- Full GitHub-style 16-week activity heatmap across all habits, with hover tooltips
- Live stats: active habits, % done today, best active streak, total check-ins
- Export / import your data as JSON (your own backup, no cloud)
- 100% client-side — all data stays in your browser's localStorage

## Why no backend?
This is intentionally a zero-dependency, zero-backend tool. Open `index.html`
and it just works — on GitHub Pages, locally, or from a USB stick.

## Stack
- Vanilla HTML / CSS / JavaScript
- localStorage for persistence
- Zero dependencies, zero build step

## Streak logic
- A "current streak" counts consecutive days ending today (or yesterday, if
  today isn't checked off yet) so you don't lose your streak display the
  moment you wake up.
- "Best streak" scans your full history for the longest consecutive run.

Made by NzJulien
