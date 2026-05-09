# Snake and Ladder Variations 🎲🐍

This project explores multiple variations of the classic Snake and Ladder game using large-scale simulations written entirely in **Python**. The goal is to analyze how changes in board design and game mechanics affect gameplay, primarily measured by the number of dice throws required to win.
- The data collected based on Snakey2023Game Repo.
- Snakey2023Game Repo. link: https://github.com/Ganesh-Eswar/Snakey2023Game
---

## Overview

The project simulates different Snake and Ladder configurations by modifying:

- Number and positions of snakes and ladders
- Grid structure (traditional and bi-directional)
- Grid size (normal and reduced)
- Dice behavior, including non-traditional and biased dice
- Total number of simulated matches per configuration

Each variation was automatically simulated **10,000 times** to ensure statistically meaningful results.

---

## Experiments Conducted

### Baseline Analysis
- No snake, no ladder
- One snake only
- One ladder only

### Traditional Board Analysis
- Multiple snakes and ladders
- Statistical metrics such as **mean** and **mode** of dice throws

### Grid Variations
- Bi-directional grids allowing both forward and backward movement
- Reduced grid sizes to study completion time impact

### Custom Dice Mechanics
- Dice range from **−3 to +3 (excluding 0)**
- Dice biasing based on player position to improve game balance

---

## Key Findings

- Board layout and grid size significantly influence game length
- Bi-directional grids greatly increase complexity and average completion time
- Dice biasing helps reduce extreme game durations while maintaining strategic depth
- Reduced grids combined with biased dice offer more balanced and engaging gameplay

---

## Purpose

This project was built as a **personal interest project** to strengthen:

- Python programming skills
- Simulation design
- Basic statistical analysis
- Data-driven reasoning and conclusions

---

## Technologies Used

- Python
- Statistical analysis (mean, mode)
- Automated simulations
