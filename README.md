# Kuramoto Model Simulations

This repository contains simulations based on the Kuramoto model, implemented using Julia and the `Pluto.jl` notebook. The Kuramoto model describes the synchronization of coupled oscillators, and its applications range from physics to biology.

## Table of Contents
- [Simulations](#simulations)
  - [1. Kuramoto Model Animation](#1-kuramoto-model-animation)
  - [2. Order Parameter vs Time](#2-order-parameter-vs-time)
  - [3. Order Parameter vs Coupling Strength](#3-order-parameter-vs-coupling-strength)
  - [4. Firefly Synchronization](#4-firefly-synchronization)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)

---

## Simulations

### 1. Kuramoto Model Animation

This simulation visualizes the phase evolution of oscillators for different coupling strengths (K) ranging from 0.1 to 10. The animation shows the synchronization dynamics over time.

**Output:** `Kuramoto_Animation.gif`

### 2. Order Parameter vs Time

Plots the synchronization order parameter over time for different values of coupling strength (K). This helps understand how the oscillators synchronize over time.

### 3. Order Parameter vs Coupling Strength

Illustrates the relationship between the coupling strength (K) and the final order parameter. This graph provides insight into the critical coupling strength required for synchronization.

**Output Graph:**

- X-axis: Coupling Strength (K)
- Y-axis: Order Parameter (r)

### 4. Firefly Synchronization

Simulates firefly synchronization based on the Kuramoto model. Fireflies are represented as glowing circles, where the brightness corresponds to their phase. The animation shows their synchronization over time.

**Output:** `fireflies_2d.gif`

---

## Setup

1. **Install Julia**: Ensure you have Julia installed on your system. You can download it from [https://julialang.org](https://julialang.org).
2. **Install Dependencies**: Open Julia and install the required packages:
   ```julia
   using Pkg
   Pkg.add(["Pluto", "DifferentialEquations", "Plots", "Statistics"])
   ```
3. **Clone the Repository**: Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/kuramoto-simulation.git
   cd kuramoto-simulation
   ```

---

## Usage

1. **Launch Pluto Notebook**:
   ```bash
   julia
   using Pluto
   Pluto.run()
   ```
2. **Open the Notebook**:
   - Load the Pluto notebook file from this repository.
   - Execute the cells sequentially to run the simulations.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The Kuramoto model is a fundamental framework in studying synchronization phenomena.
- Simulations were implemented using Julia's powerful `DifferentialEquations.jl` and `Plots.jl` libraries.
l
