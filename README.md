# Physics Lab

Physics simulations, mathematical modelling and computational experiments.

## Overview

This repository contains simulations and computational models of physical systems. Each simulation emphasizes:

- Clear statement of assumptions
- Mathematical model documentation
- Implementation grounded in physics
- Verification against known results
- Honest discussion of limitations

## Current Status

🔵 **Learning** — Building foundational physics simulations and understanding

## Areas of Study

- **Mechanics** — kinematics, forces, motion
- **Projectile Motion** — ballistic trajectories
- **Oscillations** — springs, pendulums, harmonic motion
- **Waves** — wave propagation, interference
- **Electricity** — electric fields, basic circuits
- **Numerical Simulations** — numerical methods for physics
- **Visualisations** — animated simulations and plots

## Technology Stack

- **Python 3.x** — primary language
- **NumPy** — numerical computations
- **Matplotlib** — visualisations and plots
- **Standard Library** — core functionality

## Project Structure

```
physics-lab/
├── README.md
├── .gitignore
│
├── mechanics/
│   ├── kinematics/
│   ├── projectile-motion/
│   ├── forces/
│   └── collisions/
│
├── oscillations/
│   └── README.md
│
├── waves/
│   └── README.md
│
├── electricity/
│   └── README.md
│
├── numerical-simulations/
│   └── README.md
│
├── visualisations/
│   └── README.md
│
└── experiments/
    └── README.md
```

*Note: Subdirectories are created progressively as content is added.*

## How to Use

Each simulation typically includes:

1. **Physical Problem** — What system are we modelling?
2. **Assumptions** — What are we simplifying?
3. **Equations** — The mathematical model
4. **Implementation** — Working Python code
5. **Example** — Sample inputs and outputs
6. **Units & Constants** — What values are used?
7. **Verification** — How do we know it's correct?
8. **Limitations** — What could be improved?

Example structure:
```
mechanics/
└── projectile-motion/
    ├── README.md
    ├── projectile_motion.py
    ├── simulation_output.png
    └── test_projectile_motion.py
```

## Roadmap

- [ ] Projectile motion simulator
- [ ] Simple harmonic motion (spring)
- [ ] Basic orbital mechanics
- [ ] Collision simulations
- [ ] Wave propagation
- [ ] Numerical integration methods (RK4, etc.)
- [ ] 2D rigid body dynamics

## What I'm Learning

This repository documents my journey through computational physics:

- How to translate physical equations into simulations
- Numerical methods for solving differential equations
- Verification and validation of simulations
- Visualisation of complex phenomena
- The importance of clear assumptions and limitations

## Important Notes

Simulations in this repository are **educational models**, not production-grade physics engines. Each has documented assumptions and limitations. Always verify results against known physics and trusted sources.

## License

MIT

---

*Last updated: 2026-09-10*
