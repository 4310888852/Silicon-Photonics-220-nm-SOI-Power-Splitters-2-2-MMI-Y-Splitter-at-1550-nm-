# Silicon-Photonics-220-nm-SOI-Power-Splitters-2-2-MMI-Y-Splitter-at-1550-nm-
This repository contains the simulation, design, and validation workflow for two standard passive silicon photonics power splitters implemented on a standard 220 nm Silicon-on-Insulator (SOI) platform, operating at a central wavelength of 1550 nm.

Silicon Photonics 220 nm SOI Power Splitters (2×2 MMI & Y-Splitter at 1550 nm)
This repository contains the simulation, design, and validation workflow for two standard passive silicon photonics power splitters implemented on a standard 220 nm Silicon-on-Insulator (SOI) platform, operating at a central wavelength of 1550 nm.

📌 Project Overview
Transitioning from single-waveguide structures to multi-port passive components introduces key trade-offs between insertion loss (IL), split balance, and device footprint. This project benchmarks two fundamental splitter architectures:

2×2 MMI (Multi-Mode Interferometer) splitter based on self-imaging theory.
Y-splitter (Branching waveguide structure).

🔬 Methodology & Simulation Workflow
Design Strategy:
Initial parameter sweeps and optimizations were performed using 2D FDTD to accelerate the design cycle.
Final candidate designs were verified and fine-tuned using full 3D FDTD simulations (implemented via Meep).
Key Performance Metrics Evaluated:
Insertion Loss (ILIL)
Power Splitting Ratio / Balance
Operating Bandwidth (∼1550 nm∼1550 nmwindow)

📊 Results & Benchmarking
Comparison: Both splitters are cross-compared across 2D and 3D simulation domains in terms of loss, balance, and spectral response.
References: Results are benchmarked against PhotonForge reference designs and Zhang et al. (2013) literature findings.

📂 Repository Structure
text
├── scripts/            # Python / Meep simulation scripts
├── data/               # Transmission spectra and raw simulation outputs
├── figures/            # Field-intensity maps and comparative plots
└── README.md
