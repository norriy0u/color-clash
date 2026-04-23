# 🎯 Color Clash — React Before Your Brain Does
**VishwaNova 2026 · National Level Weboreel AI Hackathon**

> The word says RED. The color is BLUE. Click the right one before your Stroop reflex betrays you. A reaction game built on cognitive dissonance.

## ✨ Features
- 🧪 **Stroop Effect Engine:** Color words are displayed in mismatched ink colors. Players must click whether the **word text** or **ink color** matches the target — mode flips randomly each round, hijacking muscle memory.
- ⚡ **Millisecond Reaction Tracking:** Response time is captured to the millisecond via `performance.now()`. A rolling average is displayed live as a neon speedometer, color-coded green/yellow/red by percentile.
- 🌈 **Color Battle Mode:** Two-player split-screen on the same keyboard — left vs right side, first to 10 correct wins. The border between players expands toward the loser in real time.
- 📉 **Cognitive Load Score:** An algorithm tracks error patterns and reaction drift to produce a "brain fog" score — a mock cognitive load index visualized as an EEG-style Canvas waveform.
- 🏅 **Streak Multiplier:** Correct streaks trigger escalating visual effects — screen shake, particle bursts, and pitch-rising Web Audio tones that climax at a 10-streak combo.

## 🛠️ Tech Stack
- **HTML5** — `performance.now()` timing, Canvas EEG renderer.
- **Vanilla CSS3** — Split-screen border animation, streak flash effects, responsive grid layout.
- **Vanilla JavaScript** — Stroop round generator, reaction stats engine, two-player state machine.
- **Web Audio API** — Streak tone escalation, error buzzer synthesis.

## 📸 Try It Out
Double-click `index.html` in any modern browser. Challenge a friend on the same screen.

---
Built with ❤️ for VishwaNova 2026
