# Multi-domain-simulator-
Shakes, wobbles, sloppy,but it runs.

---

Multi-Domain Phase System Simulator

A React-based simulation of multi-domain adaptive systems with phase synchronization, memory droplets, and hierarchical coupling.
Visualize the dynamics of 5 interconnected domains with real-time plots and interactive controls.


---

Features

5 Interacting Domains
Each domain has active and dormant states, a capacity, and a dynamic priority.

Adaptive Coupling
Coupling between domains evolves based on phase coherence and priority differences.

Phase Synchronization
Domains follow Kuramoto-like phase dynamics to model synchronization behavior.

Memory Droplets
Periodically stores system snapshots. Coherent states can inject memory back into the simulation.

Real-time Visualization
Multiple plots for:

Active states per domain

Total utilization

Domain phases

Phase coherence

Average coupling strength

Conservation error


Interactive Controls
Start, pause, and reset the simulation with a responsive UI.



---

Demo

The UI displays:

Time: Current simulation time in seconds

Average Utilization: Percentage of total active states

Phase Coherence: Synchronization level across domains

Droplets: Count of stored memory snapshots


---

Usage

1. Run Simulation: Click Run to start real-time updates.


2. Pause Simulation: Click Pause to stop updates temporarily.


3. Reset Simulation: Click Reset to restart the system with random initial states.



Each plot updates automatically, showing the dynamics of the system over time.


---

Implementation Details

State Management: React useState and useEffect for system state and simulation loop.

Canvas Drawing: HTML5 <canvas> used for real-time plotting.

Phase Dynamics: Kuramoto-inspired synchronization algorithm.

Conservation: Total system resources are normalized to maintain a fixed sum.

Memory Injection: Stores coherent states as droplets and reinjects them when coherence is high.



---

Dependencies

React ^18.0.0

lucide-react for control icons (Play, Pause, RotateCcw, Zap)

TailwindCSS for styling (optional, adjust UI as needed)



---

License

This project is dedicated to the public domain under CC0 1.0 Universal (CC0 1.0) Public Domain Dedication.

