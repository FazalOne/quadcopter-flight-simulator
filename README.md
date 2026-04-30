# Quadcopter Flight Simulator

A Python-based quadcopter flight simulator with interactive controls, physics-based motion updates, 3D-style rendering, and an aviation-inspired HUD.

## What this project demonstrates

- 6-DOF style state simulation (position, velocity, and attitude state variables)
- Thrust/torque-driven updates using matrix-based physics calculations
- Real-time rendering loop with PyGame
- HUD overlays including pitch ladder, heading tape, and speed/altitude tapes
- Adjustable camera/FOV behavior and simulator control panel inputs

## Tech Stack

- Python
- PyGame
- NumPy

## Key Files

- `main.py` - simulation, rendering, UI controls, and HUD logic

## Run

```bash
pip install pygame numpy
python main.py
```
