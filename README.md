# Reinforcement Learning Control Benchmarks

DQN, PPO and tabular Q-learning experiments for CartPole, Breakout and Pendulum.

**Technologies:** Python · Gymnasium · Stable-Baselines3 · PyTorch

## What is included

- Canonical experiments in notebooks/ with descriptive environment and algorithm names.
- Seeded policy evaluation, training curves and checkpoint comparisons.
- Saved demonstrations in demos/ and distinct earlier runs in experiments/.

## Setup

```bash
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
jupyter lab
```

Training can require substantial compute. Atari experiments also need the environment assets requested by their notebooks. Original reports and specifications are kept locally in reports/. Course reference notebooks are outside this repository under references/reinforcement_learning_notes/.

[Portfolio index](https://github.com/Qimatxbase/engineering_portfolio)
