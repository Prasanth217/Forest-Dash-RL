# ForestDash RL Agent 🌲🏃‍♂️

This project implements a reinforcement learning agent trained using **SARSA(λ)** to explore a dynamic 7x7 grid-world called **ForestDash**. The agent learns to collect treasures, avoid wolves, and explore new tiles through reward shaping and tabular Q-learning.

## 🔍 Features

- Custom 7x7 grid environment with randomized treasure, food, and wolf placement each episode.
- SARSA(λ) agent trained over 2500 episodes.
- Reward shaping for:
  - Exploring new tiles (+2)
  - Collecting treasures (+10)
  - Avoiding camping/toggling behavior
- Anti-camping logic, sprint ability, health and cooldown mechanics.
- Google Colab notebook for training and evaluation.
- Final report and figures included in the repo.

## 📊 Report Summary

The full technical report explains:
- Environment design and randomness
- State/action space
- Training results (reward curves)
- Gameplay behavior analysis
- Reviewer feedback addressed

📄 [Read the full report here](./Forest_Dash_RL_Manuscript(1).pdf)

## 📁 Files Included

- `ForestDash.ipynb` – Main Colab notebook
- `rewards_final.png` – Training reward curve
- `stepXX.png` – Gameplay snapshots
- `Forest_Dash_RL_Manuscript.pdf` – Final academic report

## 🧠 Requirements

- Python 3
- NumPy, Matplotlib (pre-installed on Colab)


## 📬 Authors

- **Prasanth Gujjula** 
- **Vishnu Vardhan Mudha**
  
MSc Robotics and Embedded AI – Maynooth University (2025)
