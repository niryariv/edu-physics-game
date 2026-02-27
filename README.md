# Physics Game — Interactive Newton's Laws for 11-Year-Olds

**Live site:** https://niryariv.github.io/edu-physics-game/

An interactive physics education game designed for ~11-year-olds (7th grade). Students explore Newton's Laws, Energy conservation, and Gravity by adjusting formula parameters and trying to hit specific in-game goals.

Available in **English** (`index.en.html`) and **Hebrew** (`index.html`, default).

---

## Lessons

| # | Topic | Formula | Goal |
|---|-------|---------|------|
| 1 | Newton's 1st Law — Inertia | d = v₀² ÷ (2 × μ × 9.8) | Slide the puck to stop at exactly 80 m |
| 2 | Newton's 2nd Law — F = ma | a = F ÷ m | Knock down the tower at 60 m (hit at ≤25 m/s) |
| 3 | Newton's 3rd Law — Action & Reaction | Thrust = burn rate × exhaust speed | Land balloon at 3 m; launch rocket to 500 m orbit |
| 4 | Conservation of Energy | v = √(2 × g × h) | Complete the loop-the-loop at ≥14 m/s |
| 5 | Gravity & Projectile Motion | Range = v₀² × sin(2θ) ÷ g | Land the probe on the pad at 150 m |

Each lesson includes:
- A live formula card that updates as sliders change
- A canvas simulation driven by real physics
- A specific goal the student must achieve by tuning the parameters
- A short inline quiz to check understanding
- A progression link connecting it to the previous lesson

---

## Structure

```
index.html        Hebrew version (default)
index.en.html     English version
```

Single-file apps — no build step, no dependencies. Open in any browser.

---

## Running Locally

```bash
# Any static file server works, e.g.:
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` / `index.en.html` directly in a browser.
