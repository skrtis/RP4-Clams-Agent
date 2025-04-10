# Malpeque Disease ABM Simulation

<p align="center">
<img src="images/BTNet_logo_dark_green.jpg" alt="BTNet Logo" width="300">
</p>

## Overview

This repository contains an agent-based model (ABM) simulation for studying the spread of bivalve transmissible neoplasia (BTN) of clam populations in Malpeque Bay, PEI. Features include fluid dynamics, disease transmission, and treatment interventions.

## Demo

https://github.com/user-attachments/assets/94add4cb-dc54-4031-af4f-f188cd748828




## Features

- Fluid dynamics simulation with semi lagrangian advection and projection (Gauss Seidel Red-Black)
- Ocean current modeling
- Disease transmission with compartment modelling
- Treatment intervention scenarios
- Population health tracking and visualization
- Animated visualizations of disease spread

## Repository Structure

- [`abm.py`](abm.py): Core agent-based model implementation with visualization functions
- [`animation.py`](animation.py): Animation generation module for creating mp4 visualizations
- [`disease.py`](disease.py): Disease transmission and progression logic
- [`grid_generator.py`](grid_generator.py): Creates the simulation grid environment
- [`mechanisms.py`](mechanisms.py): Fluid dynamics and physical mechanisms
- [`identify_populations.py`](identify_populations.py): Tools for identifying distinct clam populations
- [`visuals.py`](visuals.py): Additional visualization utilities

## Getting Started

1. Clone this repository
2. Install required dependencies
3. Run a simulation:

```python
python animation.py
