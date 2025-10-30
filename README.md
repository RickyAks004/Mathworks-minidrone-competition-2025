# 🛸 MathWorks Minidrone Competition 2025 — Team DRANZER

**Competition Project:** *Mini-Drone Competition – Two-Crown Navigation Algorithm*  
**Duration:** July 2025 – September 2025  
**Venue:** IIT Hyderabad (TiHAN)  
**Achievement:** 🏆 *Secured 4th Place | Advanced to Final Round (Top 10 Teams)*  

---

## 🚀 Overview

This repository contains **Team DRANZER**’s official submission for the **MathWorks MiniDrone Competition 2025**, featuring a **vision-based flight control and navigation system** for the **Parrot Minidrone**.  

The project integrates **image processing, nonlinear path planning, and autonomous control** using **MATLAB®, Simulink®, and Stateflow®**. It demonstrates a robust **Two-Crown Navigation Algorithm** capable of guiding a drone autonomously through two concentric crown-shaped gates in simulation.

---

## 🎯 Key Highlights

- ✈️ **Two-Crown Navigation Algorithm** — enables real-time guidance using visual circle detection and centroid tracking.  
- 🔄 **Integrated Nonlinear Path Planner** — modular planners for **X, Y, and Z** trajectories, allowing scalable mission configurations.  
- 🎥 **Vision-Based Control** — combines **Simulink Image Processing** with adaptive gain tuning in control loops.  
- 🧮 **Validated in Simulation** — achieved:
  - **Max Error (MaxE):** 0.24 m  
  - **Mean Absolute Error (MAE):** 0.15 m  
  - **Course Length:** 6.5 m  
- 🧠 **Fully Modeled in MATLAB/Simulink** — for control, perception, and state estimation.

---

## 🧩 Project Structure

```
Mathworks-minidrone-competition-2025/
│
├── controller/          # Drone control systems (PID, cascaded loops, Stateflow logic)
├── libraries/           # Custom Simulink library blocks
├── linearAirframe/      # Linearized dynamic models for analysis and tuning
├── mainModels/          # Primary competition models
├── nonlinearAirframe/   # Nonlinear simulation and validation models
├── resources/project/   # Resource and configuration files
├── support/             # Support scripts and helper functions
├── tasks/               # Mission-specific task files
├── tests/               # Simulation validation and test scripts
├── utilities/           # Custom plotting, post-processing utilities
├── work/                # Simulink work directory
│
├── variables.m          # Simulation parameters and constants
├── MinidroneCompetition.prj  # MATLAB project file
├── LICENSE              # MIT License
├── .gitignore           # MATLAB/Simulink ignore configuration
└── README.md            # Documentation
```

---

## ⚙️ Tools & Technologies

- **MATLAB® R2024b**
- **Simulink®**
- **Stateflow®**
- **Image Processing Toolbox**
- **Aerospace Blockset**
- **Control System Toolbox**

---

## 🧑‍💻 Contributors

| Name | GitHub |
|------|-------|
| **Ayush Kumar Sahu** | [@RickyAks004](https://github.com/RickyAks004) |
| **Haimavatinandan Pati** | [@Haimavatinandan2004Pati](https://github.com/Haimavatinandan2004Pati) 
| **Anup Asish Dash** | — |

---

## 🏁 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Haimavatinandan2004Pati/Mathworks-minidrone-competition-2025.git
   ```
2. **Open MATLAB and load the project:**
   ```matlab
   openProject('MinidroneCompetition.prj');
   ```
3. **Run the main Simulink model:**
   Open the file in the `mainModels/` directory and start the simulation.  
4. **Adjust variables:**  
   Modify mission parameters in `variables.m` for different flight scenarios.  
5. **Analyze results:**  
   Use scripts in the `utilities/` folder for data visualization and performance evaluation.

---

## 🏆 Competition Result

**Event:** MathWorks MiniDrone Competition 2025, IIT Hyderabad (TiHAN)  
**Team:** DRANZER  
**Achievement:** 🥇 *Secured 4th Place*  
**Recognition:** Advanced to the **Final Round (Top 10 Teams)** for outstanding performance in control design and vision-based navigation.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute with proper attribution.

---

## 🙏 Acknowledgments

Special thanks to **MathWorks**, **IIT Hyderabad (TiHAN)**, and the **MathWorks Student Competitions Team** for providing the platform, resources, and support.  
We also extend our gratitude to our mentors and university for their guidance throughout the competition.
