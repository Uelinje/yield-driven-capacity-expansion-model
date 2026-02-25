
# Yield-Driven Capacity Expansion Model  
## 9.96 GW → 15.14 GW Without Additional Pullers

---

## Executive Summary

This project models how upstream process improvements in solar manufacturing
(puller yield, cycle time reduction, wafer thickness reduction,
kerf optimization, and wafering yield improvements)
cascade multiplicatively to unlock large-scale capacity expansion
without increasing equipment count.

Using 672 CZ pullers:

- **Baseline capacity:** ~9.96 GW  
- **Improved capacity:** ~15.14 GW  
- **System amplification:** 1.52×

The model demonstrates how engineering optimization acts as a
capital-equivalent lever.

---

## Key Business Impact

### Capital Avoidance
- Pullers avoided: ~350 units  
- Direct Capex avoided: **~$105 Million USD**

### Utility Avoidance
- Annual energy avoided: ~272 GWh  
- Annual electricity savings: **~₹190 Crore**

Strategic insight:
Yield and wafer improvements can replace physical expansion.

---

## Sensitivity Analysis

Capacity modeled as a function of:

- Puller Yield (89% – 94%)
- Wafer Thickness (100 µm – 140 µm)

### 3D Capacity Surface

![Capacity Surface]![Capacity Surface](images/capacity_surface.png)

### Capacity Contour Map

![Capacity Contour]![Capacity Contour](images/contour_plot.png)

Findings:
- Wafer thickness reduction is a nonlinear amplification lever.
- Puller yield acts as a multiplicative scaling factor.
- Combined improvements create strong system-level expansion.

---

## Risk-Adjusted Capacity (Monte Carlo Simulation)

Uncertainty modeled in:

- Puller yield (σ = 0.8%)
- Cycle time (σ = 5 hours)
- Wafer thickness (σ = 5 µm)

### Monte Carlo Distribution

![Monte Carlo Distribution]![Monte Carlo Distribution](images/monte_carlo_distribution.png)

### Results

- Mean capacity: ~15.16 GW  
- Std deviation: ~0.58 GW  
- Probability of capacity < 15 GW: ~40%  
- Required buffer for 95% confidence: ~0.76 GW  

Strategic insight:
Deterministic planning must include reliability margins.



---

## Project Structure
yield-driven-capacity-expansion-model/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│ ├── 01_cascade_model_baseline_vs_improved.ipynb
│ ├── 02_capex_avoidance_analysis.ipynb
│ └── 03_sensitivity_surface_analysis.ipynb
│
└── images/

---

## Technical Stack

- Python
- NumPy
- Matplotlib
- Monte Carlo simulation
- Sensitivity surface modeling

---

## Skills Demonstrated

- Manufacturing yield cascade modeling  
- Throughput amplification mathematics  
- Capex avoidance analysis  
- Energy economics modeling  
- Nonlinear sensitivity surface analysis  
- Monte Carlo risk simulation  
- Reliability-based capacity planning  

---

## Strategic Relevance

This project demonstrates how process yield improvements translate directly
into capital avoidance, utility savings, and risk-adjusted capacity planning.

It bridges engineering optimization with financial impact modeling,
positioning yield as a strategic manufacturing lever.

