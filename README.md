# LEO-Conflict-Simulation
A basic 2D simulation for LEO satellite conflict scenarios

# LEO Conflict Simulation: A Beginner's AI Project for Space Wargaming Fundamentals

## Project Overview
This project explores the fundamentals of simulating Low Earth Orbit (LEO) satellite constellations and introduces basic conflict scenario analysis. Developed as a beginner-level AI project, it aims to build foundational skills in simulation, visualization, and potential reinforcement learning applications, relevant for aspiring professionals in space operations and defense.

This initial version focuses on a simplified 2D simulation to visualize satellite movement and introduce basic interaction logic.

## Military Relevance (Air Force / Space Force)
This project is inspired by the critical need for advanced simulation and wargaming capabilities in modern space defense. Understanding satellite orbital mechanics, collision avoidance, and strategic positioning are foundational for developing future capabilities in Space Domain Awareness (SDA) and Space Battle Management. This prototype lays groundwork for more complex scenarios involving asset protection, threat detection, and optimized maneuvering in a contested LEO environment.

## Technical Approach
* **Environment:** Google Colab (Python 3)
* **Core Libraries:** NumPy for numerical operations, Matplotlib for 2D visualization, Gym for environment definition (future RL integration), TensorFlow for potential agent training.
* **Simulation Focus:** Simplified 2D orbital paths, basic collision detection logic, and event handling.
* **Future Vision:** Expand to 3D, incorporate real orbital mechanics, develop AI agents for autonomous maneuvering, and simulate more complex wargaming scenarios.

## How to Run This Project
1.  **Open in Google Colab:** Click on the `LEO_Conflict_Simulation_v1.ipynb` link in the `notebooks/` directory of this repository. This will open the notebook directly in Google Colab.
2.  **Enable GPU Runtime:** In Colab, go to `Runtime` > `Change runtime type` > `Hardware accelerator` > `GPU`.
3.  **Run All Cells:** Go to `Runtime` > `Run all` (or execute cells one by one). The notebook will install necessary libraries, set up the simulation, run it, and display visualizations.

## Project Structure
LEO-Conflict-Simulation/
├── README.md                 # Project overview and instructions
├── notebooks/
│   └── LEO_Conflict_Simulation_v1.ipynb # The main Colab notebook
├── src/                      # (Future) For modular Python scripts
├── data/                     # (Future) For any simulation parameters or datasets
├── results/                  # (Future) For saved simulation outputs or visualizations
├── docs/                     # (Future) For additional project documentation
└── requirements.txt          # Lists Python library dependencies

## Results Summary (Will be updated as project progresses)
[Briefly summarize what your simulation demonstrates once you have initial results, e.g., "Successfully simulates 5 satellites in circular orbits, demonstrating basic collision detection alerts."]

## Future Expansion Plans
* Implement 3D visualization using Plotly.
* Integrate more realistic orbital mechanics (e.g., using Astropy or Skyfield).
* Develop a reinforcement learning agent for autonomous collision avoidance.
* Add advanced wargaming scenarios (e.g., communication link disruption, target tracking).

---
**Author:** Bryan G. Anderson/banderson1000]
**Date:** [Current Date, e.g., June 3, 2025]
