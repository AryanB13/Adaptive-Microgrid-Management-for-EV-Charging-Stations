# EV Charging Energy Management System

## Overview

This project implements an intelligent Energy Management System (EMS) for efficient Electric Vehicle (EV) charging using Reinforcement Learning (RL). The system optimizes power utilization from multiple sources: grid, photovoltaic (PV) systems, and battery storage.


## Features

- Utilizes real-world EV charging data from Texas (sourced from AFDC EVI-Pro Lite tool)
- Implements a custom OpenAI Gym environment for the microgrid
- Uses Deep Q-Network (DQN) for learning optimal energy management policies
- Balances power from grid, PV, and battery storage
- Visualizes key metrics including battery profile, state of charge, and grid power usage


## Project Structure

- `energy_management_system.py`: Main script containing the RL environment, DQN agent, and training loop
- `data/`: Directory containing data files
- `results/`: Directory containing the graphical results during training

## Key Components

1. **MicrogridEnv**: Custom OpenAI Gym environment simulating the microgrid
2. **DQNAgent**: Implementation of the Deep Q-Network agent
3. **Data Processing**: Functions to load and process MATLAB data files
4. **Visualization**: Matplotlib-based plotting functions for result analysis

## Results

The project generates several visualizations:

- Battery power profile
- Battery state of charge over time
- Grid power usage
- EV load profile
- PV generation profile
