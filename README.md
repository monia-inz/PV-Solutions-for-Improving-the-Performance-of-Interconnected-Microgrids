# PV Solutions for Improving the Performance of Interconnected Microgrids
### Research Paper 2023 | UTBM – University Technologie Belfort Montbeliard

**Authors:**  
- INZOUDDINE Monia — monia.inzouddine@utbm.fr  
- DIENG Mor — mor.dieng@utbm.fr  

*ORCID: 0000-0001-5418-7585 (Monia) · 0000-0001-7878-2071 (Mor)*

---

## Abstract

Energy storage enhances efficiency and facilitates the integration of variable renewables,
offering increased security and flexibility to networks. Solar energy, harnessed through
**photovoltaic (PV) panels**, plays a pivotal role in reducing CO₂ emissions, minimizing
pollutant releases, and preserving natural resources.

This article examines the **weaknesses of photovoltaic panels**, focusing on the **voltage
profile**, and explores solutions implemented to ensure their **optimal performance** within
interconnected microgrids.

---

## Keywords

`Smart Grids` · `IoT` · `Distribution Networks` · `Metaheuristics`  
`Voltage Improvement` · `Power Losses Minimization` · `Photovoltaics` · `Microgrids`

---

## Objectives

- Analyze the **weaknesses of PV panels** in interconnected microgrid environments
- Improve **voltage profiles** in distribution networks with high PV penetration
- Minimize **power losses** through optimized PV allocation
- Explore **metaheuristic optimization** methods for PV integration
- Study grid-connected microgrid behavior with distributed generation units

---

## Key Concepts

| Concept | Description |
|---------|-------------|
| **Microgrid** | Local energy network with distributed generation units controlling real & reactive power |
| **PV Panel** | Photovoltaic solar panel – converts sunlight into electricity |
| **Smart Grid** | Intelligent electrical grid integrating IoT and advanced control |
| **Metaheuristics** | Optimization algorithms (GA, PSO…) for complex energy allocation problems |
| **BESS** | Battery Energy Storage System – supports grid stability |
| **BSP** | Bus Supply Point – connection point to main utility grid |
| **HVDC** | High Voltage Direct Current transmission system |

---

## Repository Structure

```
/
├── paper/                        # Full research article (PDF)
│   └── PV_solutions_microgrids_2023.pdf
├── simulations/                  # Simulation models & scripts
│   ├── voltage_profile/          # Voltage improvement models
│   ├── power_losses/             # Power loss minimization
│   └── microgrid_model/          # Interconnected microgrid setup
├── algorithms/                   # Metaheuristic optimization scripts
│   ├── GA_ANFIS/                 # GA-ANFIS controller
│   └── two_thirds_optimization/  # Two-thirds voltage control method
├── figures/                      # Result plots & diagrams
├── data/                         # Network & simulation datasets
└── README.md
```

---

## Methods & References

| Method | Source |
|--------|--------|
| GA-ANFIS controller for hybrid PV-wind microgrid with BESS | Aloo et al. [1] |
| Two-thirds optimization for voltage control in distribution networks | Alrasdi et al. [2] |
| SUIEC simulation in San Juan de Mozarrifar | Caballo et al. [3] |
| Economics of distributed PV in developing countries | Timilsina [4] |
| Renewable energy in future energy needs | Gross [5] |
| Modular simulation for renewable energy systems | Bialasiewicz [6] |
| Power electronics in renewable generation & HVDC | Sun et al. [7] |
| Segmentation of medium voltage network into microgrid | Kyeremeh et al. [8] |

---

## Requirements

- **MATLAB / Simulink** (R2021b or later recommended)
- Toolboxes:
  - Simscape Electrical – Specialized Power Systems
  - Optimization Toolbox
  - Control System Toolbox

---

## Authors & Contact

| Name | Affiliation | Email | ORCID |
|------|-------------|-------|-------|
| INZOUDDINE Monia | UTBM, France | monia.inzouddine@utbm.fr | 0000-0001-5418-7585 |
| DIENG Mor | UTBM, France | mor.dieng@utbm.fr | 0000-0001-7878-2071 |

*Corresponding author: haitham.s.ramadan@gmail.com*

---

## License

This work is intended for **academic and research purposes only**.  
All rights reserved to the authors. Please cite this paper if used as reference.
