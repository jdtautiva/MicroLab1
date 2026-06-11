# MicroLab — Economics Decision Simulator

> **Interactive short-run cost and supply simulator for Managerial Economics courses.**
> Developed by **Julián Díaz Tautiva, PhD**

---

## Overview

MicroLab is a browser-based pedagogical simulation tool designed for undergraduate and graduate economics courses. Students take on the role of managers of a bakery firm and make production decisions across four rounds, each targeting a core microeconomic concept in cost theory and short-run supply.

The simulator runs entirely as a single self-contained HTML file — no backend, no installation, no dependencies beyond a modern browser. It can be served from any web server or opened locally.

---

## Learning Objectives

By completing the simulation, students are able to:

- Derive marginal cost (MC), average variable cost (AVC), and average total cost (ATC) from a quadratic cost function
- Apply the profit-maximization condition **P = MC** in a perfectly competitive market
- Evaluate the short-run shutdown condition **P ≥ AVC minimum**
- Analyze the effect of an input cost shock on optimal quantity and the shutdown point
- Construct three points of a firm's short-run supply curve and interpret its slope
---

## Key Features

**10 differentiated firms** — each group selects a unique firm with distinct parameters (FC, a, b), preventing result-sharing between teams. Parameters are hidden until a firm is selected and locked once the simulation begins.

**Interactive cost table** — CT and CV are pre-calculated and displayed. Students manually compute MC, AVC, and ATC and enter values cell by cell. Each cell validates in real time (green = correct ±$1 USD, red = revise). The table window is dynamically centered to always include both the equilibrium point and the optimal quantity.

**Automatic chart** — once all 36 cells are correct, a Chart.js graph appears automatically showing ATC, MC, the market price line, and the long-run equilibrium point. No chart is shown before the table is completed.

**Motivational feedback** — incorrect production decisions receive progressive economic hints rather than direct answers. The simulator never reveals the correct quantity outright.

**Group conclusion per round** — after each correct decision, groups must write a brief reflection before advancing. Conclusions are stored and included in the final report.

**PDF export** — upon completing all four rounds, groups download a full report including: results per round, group conclusions, performance feedback based on average attempts, reinforcement of the key economic concept per round, and five discussion questions for the plenary.

---

## Technical Details

| Attribute | Detail |
|---|---|
| Format | Single `.html` file, fully self-contained |
| Dependencies | Chart.js 4.4.1 (CDN), jsPDF 2.5.1 (CDN), Google Fonts (CDN) |
| Backend required | None |
| Browser support | Any modern browser (Chrome, Firefox, Safari, Edge) |
| Screen | Desktop optimized; responsive down to tablet |
| Language | Spanish (es-CL) |

---
## Suggested Citation

Díaz Tautiva, J.A. (2026). *MicroLab — Economics Decision Simulator*. Managerial Economics teaching simulator.

---
## License
This project is intended for educational use. Add the preferred license for your course, institution, or repository before publication.
