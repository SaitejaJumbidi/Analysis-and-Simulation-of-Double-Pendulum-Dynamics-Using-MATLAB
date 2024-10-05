# Analysis and Simulation of Double Pendulum Dynamics Using MATLAB

## Project Overview
This project simulates the motion dynamics of a double pendulum using MATLAB's ODE45 solver. The system's behavior is analyzed through visualizations of angular displacements, velocities, and real-time animations of the pendulum's movement. The project explores how the complex, non-linear dynamics of the double pendulum can produce both periodic and chaotic motion.

## Features
- **ODE45 Solver Implementation:** Models the dynamic motion equations of a double pendulum system.
- **Graphical Visualizations:** Plots time-based changes in angular positions and velocities for both pendulums.
- **Real-Time Animation:** Animates the movement of the pendulums based on the computed positions over time.
  
## Project Structure
- `Project1.m`: Main MATLAB script for simulating the double pendulum.
- `Project1.2.pdf`: Documentation of results, including visualizations of angles, velocities, and system analysis.
  
## How to Run the Simulation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/SaitejaJumbidi/Analysis-and-Simulation-of-Double-Pendulum-Dynamics-Using-MATLAB.git
2. Open `Project1.m` in MATLAB.
3. Run the script. The simulation will:
   - Compute the angular positions and velocities of both pendulums over a 10-second interval.
   - Generate plots showing angular displacements θ1, θ2 and angular velocities (dθ/dt).
   - Display a real-time animation of the pendulum's movement.

## Simulation Parameters
- **Initial Conditions:**
  - θ1 = 60° (pendulum 1 initial angle)
  - θ2 = 45° (pendulum 2 initial angle)
  - dθ1/dt = 0, dθ2/dt = 0
  
- **Physical Parameters:**
  - Gravity, g = 9.81 m/s^2
  - Pendulum lengths: l_1 = 1 m, l_2 = 1.5 m
  - Masses: m_1 = 2kg, m_2 = 1kg

## Results
- Time-based plots of angles θ1, θ2 and angular velocities highlight the dynamic motion.
- A phase space plot demonstrates the relationship between angular positions and velocities.
- The animation visually represents the motion of the double pendulum system in real time.
