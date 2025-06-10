# NetLogo Fox-Rabbit Ecosystem Model

This is a predator-prey simulation built using **NetLogo**, modeling the interaction between **foxes** (predators), **rabbits** (prey), and **grass** (resource). The model demonstrates ecological dynamics such as hunting, food consumption, energy gain/loss, and reproduction.

## 🧠 Overview

The simulation explores:
- How predator and prey populations fluctuate over time
- The role of energy in survival and reproduction
- Grass regrowth and its impact on the ecosystem

## ⚙️ Parameters (Sliders)

| Slider Name              | Description                                 | Default |
|--------------------------|---------------------------------------------|---------|
| `initial-rabbits`        | Number of rabbits at the start              | 100     |
| `initial-foxes`          | Number of foxes at the start                | 50      |
| `grass-regrowth-delay`   | Time for grass to grow back on patches      | 35      |
| `rabbit-gain-from-food`  | Energy rabbits gain from eating grass       | 10      |
| `rabbit-reproduce`       | Chance a rabbit reproduces per tick         | 0.15    |
| `fox-reproduce`          | Chance a fox reproduces per tick            | 0.04    |

## Plots

- `Grass`: Number of patches with grass
- `Rabbits`: Total number of rabbits
- `Foxes`: Total number of foxes

## Monitors

- Current rabbit count
- Current fox count

## How to Run

1. Open the model in **NetLogo**.
2. Adjust the sliders as desired.
3. Click `setup` to initialize.
4. Click `go` to run the simulation.

## 📚 Concepts

- Predator-prey dynamics
- Energy modeling
- Agent-based modeling
- Grass regrowth and resource competition
