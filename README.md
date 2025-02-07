# Projectile Motion Simulation with and without Air Resistance

## Description
This project simulates projectile motion considering both freefall and air resistance using numerical methods. The animation compares the trajectories of a projectile under both conditions.

## Features
- Computes projectile motion with and without air resistance.
- Solves second-order differential equations using `odeint`.
- Generates an animated plot of the projectile’s trajectory.

## Requirements
Make sure you have the following Python libraries installed:
```bash
pip install numpy matplotlib scipy
```

## Usage
Clone the repository and run the script:
```bash
git clone <repository_url>
cd <repository_name>
python script.py
```

## Parameters
- `α`: Friction coefficient
- `h`: Initial height (m)
- `v_0`: Initial velocity (m/s)
- `theta`: Launch angle (°)
- `g`: Acceleration due to gravity (m/s²)

## Output
The script produces an animated plot comparing the projectile’s motion under freefall and air resistance. The blue trajectory represents freefall, while the red trajectory accounts for air resistance.

## Author
Hugo Alexandre

