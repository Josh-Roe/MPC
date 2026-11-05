# Model Predictive Control with Single-Shot Object Recognition for Automobile Safety

Science research project by Josh Roe and Connor Lee, October 2024 – February 2025. It placed 3rd in Robotics and Intelligent Machines at the 2025 Palos Verdes Peninsula Science Fair.

A VEX model vehicle was built to test a local, predictive approach to autonomous collision avoidance. It combines:

- **Odometry** for localization from motor encoders
- **Dynamic Window Approach (DWA)** for path planning around obstacles
- **Model Predictive Control (MPC)** for path following
- **Single-Shot Detection (SSD)** for object recognition on a Raspberry Pi 4 with an Intel D435i depth camera

## Results

| Measure | Result |
| --- | --- |
| Obstacle avoidance success | 98% over 50 trials |
| MPC path deviation | 0.323% |
| Pure Pursuit path deviation | 10.236% |
| Maximum odometry pose error | 14.113 mm |

## Documents

- [Poster](docs/poster.pdf)
- [Abstract](docs/abstract.pdf)

## Tools

C++, PROS, Python, TensorFlow, Qt Creator, MATLAB, and Onshape.
