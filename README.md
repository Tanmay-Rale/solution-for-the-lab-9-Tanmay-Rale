# ELEC5308 — Lab 9: Planning and Decision Making

---

## Overview

In this lab you will work through a **single running example**: a compact weighted road network that represents a stylised city block.
The same world is handed progressively through all four layers of the autonomous-driving hierarchy:

| Layer | Question answered | Section |
|---|---|---|
| **Route planning** | Which sequence of roads minimises travel cost? | 1 |
| **Behaviour planning** | Which atomic manoeuvre should execute next? | 2 |
| **Motion planning** | What is the safest, smoothest physical trajectory? | 3 |
| **Decision under uncertainty** | How does stochastic sensing change the plan? | 4 |

### Mandatory Task (20 marks)
Implement **Dijkstra's algorithm** and **A\* search** inside the scaffold functions in **Section 1**.  
These are autograded via Gradescope.

### Optional Tasks (not marked, highly recommended)
- **Optional A** — Finite-State Machine & rule explosion (Section 2)
- **Optional B** — Trajectory objective function & weight policies (Section 3)
- **Optional C** — MDP value iteration & risk shadows (Section 4)

### Optional Task with Extra Marks
- **Optional D** — Apply a planning algorithm inside `highway-env` and upload a simulation video to Canvas (Section 5)

---

> You are the *supervisor*. Use AI tools to help you write and debug code, but critically verify every output. Ask yourself: *Is this result correct? Why? What would break it?*

---
