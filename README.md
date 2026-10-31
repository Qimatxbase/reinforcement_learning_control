# Reinforcement Learning Control Benchmarks

DQN, PPO and tabular Q-learning experiments for CartPole, Breakout and Pendulum.

**Technologies:** Python · Gymnasium · Stable-Baselines3 · PyTorch

## Academic context

Completed as **UTS 43008, Assessment 2**, an **individual assessment** exploring reinforcement-learning control across CartPole, Breakout and Pendulum.

The repository includes assessment workflows and preserved experiment variants. External libraries, environment implementations and any cited reference material retain their original authorship.

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
