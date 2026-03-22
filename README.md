# Robo-Rally 🤖

A browser-based obstacle course game with **30 levels** ranging from Easy to Extreme Demon, phonk background music, and scream sound effects when you fall in the lava!

## 🕹️ Play Now

**[▶ Click here to play!](https://family-ai-coding-playground.github.io/obby-game/)**

---

## Controls

| Key | Action |
|-----|--------|
| `←` / `A` | Move left |
| `→` / `D` | Move right |
| `Space` / `↑` / `W` | Jump |
| Jump again mid-air | Double jump |

---

## Difficulty Curve

| Stages | Difficulty | Platform Width | Speed |
|--------|-----------|---------------|-------|
| 1–5   | Easy       | 120–200px | ≤1.1 |
| 6–10  | Normal     | 90–120px  | ≤2.0 |
| 11–15 | Hard       | 48–90px   | ≤2.5 |
| 16–20 | Harder     | 40–55px   | ≤3.0 |
| 21–25 | Insane     | 30–44px   | ≤3.5 |
| 26    | Easy Demon 😈 | 24–28px | ≤3.8 |
| 27    | Medium Demon 😈😈 | 20–25px | ≤4.2 |
| 28    | Hard Demon 😈😈😈 | 18–22px | ≤4.5 |
| 29    | Insane Demon 😈😈😈😈 | 15–20px | ≤5.0 |
| 30    | Extreme Demon ☠ | 14–16px | ≤6.2 |

---

## Platform Types

| Color | Type | Behaviour |
|-------|------|-----------|
| 🟩 Green | Start / Finish | Safe zones |
| 🟦 Blue | Normal | Solid platform |
| 🟣 Purple | Moving | Slides left and right |
| 🟦 Teal | Elevator | Moves up and down — rides with you |
| 🔴 Red | Bounce | Launches you super high |
| 🟠 Orange | Crumble | Shakes then disappears ~1 second after you step on it |

---

## Features

- 🎵 Phonk background music (135 BPM drum machine with 808 bass)
- 😱 Scream sound effect + text pop when you fall in lava
- 💥 Particle explosion on death
- 📊 Progress bar showing completion across all 30 stages
- 🎨 Background color changes with difficulty

---

## Deploy Your Own Copy

This game is a **single HTML file** — no build step needed.

### GitHub Pages (already set up for this repo)
1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages → Deploy from branch → main → / (root)**
3. Live at `https://<org>.github.io/<repo>/`

### Other free options
- **Netlify**: Drag and drop `index.html` at [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel**: Run `npx vercel` in the folder
- **Locally**: Just open `index.html` in any browser — no server needed!
