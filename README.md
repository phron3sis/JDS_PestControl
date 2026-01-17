# Pest Control by footballjds

Lightweight Pest Control script for **SIMBA 2.0 + WaspLib**.  
Parks at the Knight, clears Shifters, banks points.

---

## Features

- **Auto boat / plank / positioning**  
  Handles Novice, Intermediate, and Veteran boats based on combat level

- **Shifter prioritization**  
  Multiple targeting strategies per account

- **Live HUD**  
  Wins, points/hour, XP/hour, activity bar, portal HP, break timers

- **Session goals**  
  Stop after X actions or X minutes

- **Break & sleep integration**  
  Full WaspLib antiban support

- **Auto-spend**  
  Spend your points on rewards

- **User choices**  
  Disable anything you want, or enable emotes

---

## Anti-Detection
This script is built against documented **server-side behavior analysis** techniques.

**Layered implementation:**
- **Identity**  
  SHA256-seeded per-account behavioral fingerprint
- **Timing**  
  Ex-Gaussian, Weibull, and LogNormal reaction-time distributions
- **Fatigue**  
  Session-length performance degradation
- **Periodicity**  
  Per-game tempo drift, threshold variance, de-sequencing
- **Trajectory**  
  Position preference drift, multiple boat movement profiles
- **Sequences**  
  Probabilistic target selection with stickiness decay

No two accounts produce the same behavioral signature.

---

## Requirements
- SIMBA 2.0
- WaspLib
- Combat levels:
  - 40+ (Novice)
  - 70+ (Intermediate)
  - 100+ (Veteran)

---

## Setup in script form
1. Configure quick prayers if using prayer options
2. Start at the Pest Control outpost
3. Set points-per-win based on boat:
   - Novice: 3–4
   - Intermediate: 4–5
   - Veteran: 5–7

---

## Disclaimer
Personal project. Provided as-is. Use at your own risk.
