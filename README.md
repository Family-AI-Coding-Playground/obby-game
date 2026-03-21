# Obby Game 🎮

A browser-based obstacle course game with 10 levels of increasing difficulty, phonk background music, and scream sound effects when you fall in the lava!

## 🕹️ Play Now

**[▶ Click here to play!](https://family-ai-coding-playground.github.io/obby-game/)**

> It may take a minute to go live the first time GitHub Pages deploys.

---

## Controls

| Key | Action |
|-----|--------|
| `←` / `A` | Move left |
| `→` / `D` | Move right |
| `Space` / `↑` / `W` | Jump |
| Jump again in mid-air | Double jump |

---

## Levels

| # | Name | What's New |
|---|------|------------|
| 1 | Baby Steps | Tutorial — wide platforms, gentle jumps |
| 2 | Slide Show | Horizontal moving platforms |
| 3 | Sky High | Bounce pads that launch you to high platforms |
| 4 | Tight Walk | Narrow platforms, bigger gaps |
| 5 | Elevators | Vertical moving platforms that carry you up/down |
| 6 | Crumble Zone | Platforms that shake and disappear when you stand on them |
| 7 | Mix Up | All mechanics combined |
| 8 | Speed Demon | Fast movers, crumbling, elevators |
| 9 | Chaos Mode | Everything at once, tiny platforms |
| 10 | ☠ THE GAUNTLET | 22px platforms, max speed — good luck! |

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

## Deploy Your Own Copy

This game is a single HTML file — no build step needed.

### GitHub Pages (already set up for this repo)
1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set Source to `Deploy from branch` → `main` → `/ (root)`
4. Your game will be live at `https://<org>.github.io/<repo>/`

### Other free options
- **Netlify**: Drag and drop the `index.html` file at [netlify.com/drop](https://app.netlify.com/drop)
- **Vercel**: Run `npx vercel` in the folder containing `index.html`
- **Locally**: Just open `index.html` in any browser — no server required!
