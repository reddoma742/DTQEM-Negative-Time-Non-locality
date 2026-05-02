# DTQEM-Negative-Time-Non-locality
DTQEM: Negative Time &amp; Non-locality (Dual‑Time Quantum Entanglement Model)
# DTQEM: Negative Time & Non‑locality

**Dual‑Time Quantum Entanglement Model**

This repository presents a novel mathematical and philosophical model for quantum entanglement, quantum erasure, and non‑locality. The core idea is that every particle possesses **two times**: a real time \( t_r \) and a *negative* imaginary time \( t_v \) that depends on the launch angle between particles.

## Key equations

- **Effective time**  
  \( t_{\text{eff}} = t_r \bigl(1 - \alpha(\theta) \cdot K_{\text{eff}}\bigr) \)  
  with \( \alpha(\theta) = \sin(\theta/2) \)

- **Observation switch** (thermal decoherence)  
  \( K_{\text{eff}} = \exp\!\bigl(-\Gamma(T)\,t_{\text{obs}}\bigr) \)

- **Thermal decoherence coefficient**  
  \( \Gamma(T) = \Gamma_0 + aT + bT^3 + cT^7 \)

- **Planck time cutoff** (avoids mathematical infinity)  
  \( t_{\text{eff}} \ge t_{\text{Planck}} = 5.391\times10^{-44}\,\text{s} \)

- **Effective speed**  
  \( v_{\text{eff}} = d / t_{\text{eff}} \)

## Physical outcomes

- At \( \theta = 180^\circ \) (perfect opposite launch) and \( K_{\text{eff}}\approx 1 \),  
  \( v_{\text{eff}} \sim 10^{41}c \) → practically instantaneous action at any distance.
- Increasing temperature or observation time gradually destroys entanglement, returning to classical speed \( v_{\text{rel}} \).
- The model exactly reproduces the quantum eraser experiment: erasing which‑path information sets \( K_{\text{eff}}\to 1 \) and restores the fringes.

## Run the code

The Python script `DTQEM.py` requires `numpy` and `matplotlib`.  
Execute:

```bash
python DTQEM.py
