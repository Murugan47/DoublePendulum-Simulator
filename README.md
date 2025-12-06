---

## Demo

[![Play Demo](https://img.shields.io/badge/Demo-Click_here-brightgreen)](https://murugan47.github.io/DoublePendulum-Simulator/)

Click the button above to try a live WebGL demo of the game in your browser.

---

Double Pendulum Simulator (Unity)

A fully functional double pendulum simulator built in Unity, using the standard Lagrangian-derived equations of motion. This project numerically solves the coupled differential equations governing a double pendulum and visualizes the motion in real time.

Overview

Finally got around to completing this project, a fully functional double pendulum calculated using the standard Lagrangian-derived equation ported over to Unity's code. The end point of the double pendulum has a trailing circle that shows the general pattern. The angles of the arms are graphed with the X plot representing the first arm's angle and the Y plot representing the second arm's angle. It's mostly a general graph to demonstrate the overall shape of the pendulum. Most true double-pendulum systems are inconsistent and chaotic, and while this simulation captures much of that behavior, it is still an approximation and not perfectly accurate.

Features

Real Lagrangian-based physics for both pendulum arms

Trail renderer at the end mass to show motion patterns

Live angle graphing (Arm One Angle vs. Arm Two Angle)

Configurable masses, lengths, damping, and gravity

Clean Unity component structure for easy modification

How the Graph Works

X-axis: Angle of the first arm (relative to vertical)

Y-axis: Angle of the second arm (relative to vertical)

This produces a phase-like visualization of motion patterns, intended to show general behavior rather than highly precise physical states.

Notes

Numerical instability is inherent to chaotic systems—small deviations can become amplified.

Frame rate can affect integration quality depending on timestep settings.

Simulation accuracy can be improved by switching to fixed-timestep integrators or RK4 methods.
