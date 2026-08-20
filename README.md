# Focus Flow

A minimal Pomodoro-style focus timer that runs entirely in the browser — no build step, no dependencies, no backend.

## Features

- 25-minute focus sessions and 5-minute breaks, shown as a circular progress ring
- Optional task label for what you're focusing on
- A short audio chime when a session ends
- Daily count, day streak, and all-time session totals, saved locally via `localStorage`

## Usage

Open [`index.html`](index.html) directly in a browser — that's it.

```bash
open index.html
```

## How it works

Everything lives in a single self-contained file:

- Plain HTML/CSS for layout and styling
- Vanilla JavaScript for the timer logic and stats tracking
- Progress is persisted per-browser in `localStorage` under the `focusFlowData` key, so stats carry over between sessions on the same device
