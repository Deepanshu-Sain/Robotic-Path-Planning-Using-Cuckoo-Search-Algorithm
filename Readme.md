# Robotic Path Planning via Modified Cuckoo Search Algorithm

![Algorithm](https://img.shields.io/badge/Algorithm-Metaheuristic-blue)
![Domain](https://img.shields.io/badge/Domain-Robotics-red)
![Performance](https://img.shields.io/badge/Result-Superior%20Convergence-brightgreen)

## Overview
This project addresses the complex engineering challenge of **Robotic Path Planning** in high-dimensional, obstacle-rich environments. It introduces a **Modified Cuckoo Search Algorithm (Modified CSA)** that enhances the standard nature-inspired metaheuristic with **Adaptive Step Size** and **Elite Opposition-Based Learning (EOBL)**.

The proposed algorithm is validated against standard engineering benchmarks (CEC Suites) and applied to real-world navigation scenarios, demonstrating superior ability to avoid local optima compared to Genetic Algorithms (GA) and Particle Swarm Optimization (PSO).

## Key Innovations
- **Adaptive Step Size**: Dynamically adjusts the Lévy flight step scale, enabling broad global exploration in early phases and precise local exploitation in later phases.
- **Elite Opposition-Based Learning (EOBL)**: Prevents stagnation by periodically evaluating the "opposite" solution space based on elite candidates, significantly improving convergence speed.

## Technologies & Algorithms
- **Core Algorithm**: Cuckoo Search (CS)
- **Modifications**: Adaptive Lévy Flights, EOBL
- **Comparison Models**: Genetic Algorithm (GA), Particle Swarm Optimization (PSO), Ant Colony Optimization (ACO)
- **Benchmarks**: CEC 2014, 2017, 2020, 2022 Test Suites

## Simulation & Testing
The algorithm was tested on distinct robotic path planning scenarios:
1. **Obstacle Avoidance**: Navigating static environments without collisions.
2. **Time Optimization**: Minimizing total travel time.
3. **Energy Efficiency**: Optimizing path length to conserve battery.
4. **3D Terrain Navigation**: Planning paths in complex Z-axis landscapes.

## Results
- **Statistical Significance**: Confirmed via the **Wilcoxon signed-rank test**.
- **Performance**: The Modified CSA showed:
  - Faster convergence rates.
  - Lower standard deviation (higher stability).
  - Better obstacle clearance capability than base CSA and PSO.

## 👥 Contributors
- **Deepanshu Sain** (2023UCD2138) and others
- **Supervisor**: Dr. Ankur Gupta

*Department of Computer Science & Engineering (Data Science), NSUT, New Delhi.*
