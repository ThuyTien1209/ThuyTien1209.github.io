---
title: "Traveling Salesman Problem Solver with Genetic Algorithm"
summary: "Developed a GA solution for the TSP using the dataset of 63 provinces in Vietnam, with a GUI for visualization and parameter tuning."
tags:
  - Python
  - Genetic Algorithm
  - Optimization
  - GUI
date: "2025-05-26"
image:
  filename: "gui1.png"
---
### Project Overview
- Implemented **Genetic Algorithm (GA)** to solve the **Traveling Salesman Problem (TSP)**, optimizing routes across Vietnamese provinces.
- Applied key GA operators: **Tournament Selection, Single/Two-point & Order Crossover, Swap/Inverse Mutation**, with customizable parameters (population size, mutation rate, generations).  
- Conducted extensive experiments with datasets ranging from **3 to 63 cities** to evaluate effects of parameters and operators.  

### Key Results
- Achieved stable near-optimal solutions (fitness ~2300–2500 km for full Vietnam dataset).  
- Identified best-performing configurations (Order crossover + Swap mutation + Rank selection).  
- Hybrid **GA + Simulated Annealing** further improved convergence speed and solution quality.  

### Features
- Built an **interactive GUI**: users can upload city datasets, choose start points, adjust GA parameters, and visualize optimal routes on a **map interface**.  
- GUI supports **satellite map visualization** with route plotting and step-by-step path display.  

### Impact
This project demonstrates how **evolutionary algorithms can effectively tackle NP-hard optimization problems** like TSP, with direct applications in logistics, routing, and scheduling.
