# Focurio

A task planning and tracking dashboard based on the **Eisenhower Matrix** and Brian Tracy's **ABCDF** prioritization system. Simple, fast, and syncable across devices.

## ✨ Features

- **4 quadrants** by urgency and importance (Q1–Q4), with per-quadrant counts of pending, in-progress, and completed tasks.
- **A–F prioritization** within each quadrant, sorted automatically.
- **Task states**: pending, in progress, completed, and cancelled.
- **Drag & drop** to move tasks between quadrants (works with mouse and touch).
- **Instant search** by task text, tag, or subtasks.
- **Subtasks / checklist** per task, with visible, expandable progress.
- **Productivity stats**: completion rate, tasks completed in the last 7 days, and active load by quadrant and priority.
- **Free-form tags** (Personal, Work, etc.).
- **Due dates** with overdue warnings.
- **Auto-archiving** of closed tasks after 7 days, with history.
- **PDF export** (executive summary of active tasks).
- **Cloud sync** between desktop and phone via a private GitHub Gist.
- **Dark mode** and installable as an app (PWA) on mobile.

## 🚀 Usage

Open the app, add tasks with the **New task** button or the **+** in each quadrant, and manage their state with one click.

### Cross-device sync

1. Generate a GitHub fine-grained token with **Gists: Read and write** permission.
2. In the app, tap the sync pill and paste the token.
3. Repeat on your other device using the **same token**: it detects the Gist automatically.

> The token is stored only in each browser, never in the code. Data lives in a **private** Gist.

## 🛠️ Tech

Pure HTML, CSS, and JavaScript (no dependencies, no build step). Local persistence via `localStorage` with optional sync through the GitHub Gists API.

## 📌 Roadmap

- Push notifications for overdue tasks
- Recurring tasks
- Native iOS and Android app
