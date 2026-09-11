# ⚗️ Distillation Column Simulator

An interactive, browser-based distillation column simulator — no server, no dependencies, pure HTML + Canvas + JavaScript.

**[▶ Live Demo](https://krshashi000.github.io/distillation-column-simulator/distillation_column.html)**

---

## Features

| Tab | What you get |
|---|---|
| 🏭 **Column Schematic** | Clickable trays — hover for T, composition, section; live stream summary (F, D, B, L, V) |
| 📊 **McCabe-Thiele** | Live stage step-off, operating lines, q-line, pinch analysis, R/R_min |
| 🔬 **VLE Diagram** | x-y and T-xy views, azeotrope detection, relative volatility on hover |
| 📈 **Stage Profiles** | Composition (x, y) and temperature vs. stage number |

## Component Systems

- Benzene / Toluene
- **Ethanol / Water** (with azeotrope at x = 0.894)
- Methanol / Water
- n-Hexane / n-Heptane

## Interactive Controls

- Reflux ratio R
- Feed stage location
- Total theoretical stages N
- Feed composition z_F
- Feed quality q (0 = saturated vapor, 1 = saturated liquid)
- Distillate purity x_D
- Bottoms purity x_B

All charts update in real time as you move the sliders.

## Usage

Just open `distillation_column.html` in any modern browser — no install, no server needed.

## Screenshot

> McCabe-Thiele step-off with q-line, operating lines, and pinch point visualization.

---

Built with vanilla HTML5 Canvas and JavaScript.
