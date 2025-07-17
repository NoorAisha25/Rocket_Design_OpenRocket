# 🚀 Rocket Design & Simulation – OpenRocket

This repository showcases a complete rocket design and simulation project developed using **OpenRocket** as part of the **India Space Lab Winter Internship Program**. The project focuses on aerodynamic stability, motor performance, and recovery system analysis for a single-stage rocket powered by a **J90W-14 motor**.

---

##  Internship Context

This project was developed during the **India Space Lab Winter Internship**, where I explored rocket design principles, propulsion systems, and simulation tools. The goal was to design a stable, recoverable rocket and analyze its flight characteristics using OpenRocket.

---

##  Project Overview

| Parameter               | Value                      |
|------------------------|----------------------------|
| **Rocket Name**        | Rocket_Design [J90W-14]     |
| **Stages**             | 1                          |
| **Total Mass**         | 8246 g                     |
| **Stability Margin**   | 2.23 cal / 14.6%           |
| **Center of Gravity**  | 58.4 cm                    |
| **Center of Pressure** | 76.3 cm                    |
| **Motor Used**         | J90W-14                    |

---

##  Motor Performance

| Metric                 | Value                      |
|------------------------|----------------------------|
| **Average Thrust**     | 97.6 N                     |
| **Max Thrust**         | 187 N                      |
| **Burn Time**          | 7.05 s                     |
| **Total Impulse**      | 689 Ns                     |
| **Thrust-to-Weight**   | 1.21:1                     |
| **Motor Weight**       | 427 g                      |

---

##  Simulation Results

| Metric                 | Value                      |
|------------------------|----------------------------|
| **Max Altitude**       | 8.04 m                     |
| **Time to Apogee**     | 2.35 s                     |
| **Max Velocity**       | 60.3 m/s                   |
| **Velocity off Pad**   | 7.8 m/s                    |
| **Landing Velocity**   | 60.3 m/s                   |
| **Flight Time**        | 3.51 s                     |

---

##  Component Breakdown

### Nose Cone
- Shape: Ogive
- Material: Fiberglass (1.85 g/cm³)
- Length: 16 cm
- Mass: 99.5 g

### Body Tubes
- Material: Fiberglass
- Diameter: 7.74 cm / 5 cm
- Lengths: 52 cm / 46 cm
- Masses: 376 g / 278 g

### Fins
- Shape: Trapezoidal (4 fins)
- Material: Fiberglass
- Thickness: 0.2 cm
- Mass: 134 g

### Recovery System
- Parachutes: Ripstop nylon (60 cm & 100 cm)
- Shock Cord: Kevlar & Elastic cord
- Shroud Lines: Elastic cord (6 lines, 30 cm each)

### Other Components
- Centering Rings, Bulkheads, Transition Sections
- Materials: Cardboard & Fiberglass

---

## 📁 Repository Contents
Rocket_Design_OpenRocket/ │ ├── Rocket_Info.pdf               # Detailed rocket specifications ├── NoorAisha_Rocket.ork          # OpenRocket design file ├── README.md                     # Project summary │ ├── simulation_results/           # Graphs and data │   ├── altitude_vs_time.png │   ├── thrust_curve.png │   ├── stability_graph.png │ ├── photo_studio/                 # Rendered rocket image │   └── rendered_rocket.png │ ├── documentation/                # Final report (optional) │   └── Rocket_Report.pdf

## 📸 Rocket Preview

<img width="1920" height="961" alt="Rendered_Rocket" src="https://github.com/user-attachments/assets/16a2c770-3b07-48f9-9711-e868862b1751" />


---

##  References

- [OpenRocket](https://openrocket.info/)
- [ThrustCurve.org](https://www.thrustcurve.org/)
- [India Space Lab](https://indiaspacelab.in/)

---

##  Learnings

- Stability tuning using CG–CP optimization
- Motor delay troubleshooting and thrust curve analysis
- Recovery system design and parachute sizing
- Visual realism using OpenRocket’s Photo Studio




