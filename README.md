# OrbitalMechanicsSimulator
An interactive orbital mechanics simulator that visualizes planetary motion using Newton’s Law of Universal Gravitation and Kepler’s Laws through real-time physics simulation.
Introduction. Orbital mechanics is a fundamental concept in physics and space science. This project simulates the motion of a planet orbiting a massive body (the Sun) by applying Newton’s laws through numerical computation. The simulator provides a real-time visual representation of gravitational interactions and helps bridge the gap between theoretical physics and practical implementation.

# Physics Concepts Used
Newton’s Law of Universal Gravitation
𝐹=(𝐺×m₁×m₂)/𝑟^2

Where:
F = Gravitational force
G = Gravitational constant (6.674 × 10⁻¹¹ N·m²/kg²)
m₁, m₂ = Masses of the objects
r = Distance between their centers

Kepler’s Laws
First Law: Orbits are elliptical
Second Law: Equal areas are swept in equal times

Third Law: 
𝑇^2 ∝ 𝑟^3

# Experiments Performed
1. Effect of Initial Velocity on Orbit Shape
   Low velocity → Planet spirals inward
   Optimal velocity → Stable circular orbit
   High velocity → Elliptical orbit or escape
   Concept Demonstrated: Balance between gravitational force and velocity

2. Effect of Distance on Orbital Period
   Objects farther from the Sun take longer to complete an orbit
   Confirms Kepler’s Third Law

3. Gravitational Force vs Distance
   Doubling the distance reduces gravitational force to one-fourth
   Direct verification of the inverse square law

# Simulator Design & Algorithm
The simulator uses numerical integration (Euler method) to approximate continuous orbital motion by dividing time into small steps.

Algorithm Steps:
Initialize physical constants and starting conditions
Calculate distance between planet and Sun
Compute gravitational force magnitude and direction
Calculate acceleration using  a=F/m
Update velocity using time step
Update position using new velocity
Repeat for each frame

# Technologies Used

HTML – Structure
JavaScript – Physics calculations and simulation logic
Canvas API – Real-time visualization
Euler Method – Numerical integration

# Real-World Applications
Orbital mechanics is the foundation of modern space technology:

# Satellite Technology
GPS navigation
Satellite TV and weather forecasting
Low Earth Orbit (LEO) internet satellites

# Space Exploration
Planetary trajectory planning
Fuel-efficient orbital transfers
Mars and deep-space missions

# Planetary Defense
Predicting asteroid and comet paths

# Conclusion

This project demonstrates how simple physical laws govern complex cosmic motion. By combining physics theory with computational simulation, the orbital mechanics simulator provides a clear understanding of how planets, satellites, and spacecraft move through space. These same principles enable modern technologies ranging from GPS systems to interplanetary missions.

# Project Use Case
Physics academic project
Learning numerical methods
Understanding orbital motion
Demonstrating real-world physics applications
