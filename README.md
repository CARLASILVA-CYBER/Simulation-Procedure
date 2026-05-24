Quantum-Inspired Stackelberg APT Defense Simulation

This repository provides the simulation code supporting the paper:

"Quantum-Inspired Adversarial Risk Optimization for AI-Driven APT Defense in Dynamic Stackelberg Games"

The simulation evaluates a mathematical framework for AI-driven defense against Advanced Persistent Threats (APTs). Cyber events are represented as complex-valued risk signals, temporal coherence is estimated for each asset, and defensive resource allocation is optimized using a Stackelberg game formulation.

## Main Features
- Synthetic generation of normal and APT-like cyber events
- Complex-valued risk representation: z_k = s_k exp(i theta_k)
- Temporal coherence estimation
- Quantum-inspired strategic probability weights
- Comparison of defensive strategies:
  - Random defense
  - Uniform defense
  - Risk-based defense
  - Stackelberg-optimized defense
- Evaluation metrics:
  - Adversarial risk
  - Residual risk ratio
  - Risk reduction gain
  - Defense efficiency
  - Strategy stability
  - 
## How to Run
```bash
pip install -r requirements.txt
python main.py
