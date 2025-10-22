# PhaseOS-Interface
Streamlit-based prototype for Phase-OS Interface

## Overview
This repository hosts the Streamlit interface for the **Phase-OS** project.
It provides a modular, offline-ready UI to visualize and control Phase-OS
simulation results (Phases 1–7) independently of the main Rust engine.

## System Architecture

Windows 11 (Codex)
  └── PhaseOS-Interface  ← Streamlit UI prototype
        ├── app_phaseos.py
        ├── python/phase_plots_plos_complete.py
        └── requirements.txt
Ubuntu 24.04 (Air-gap)
  └── Phase-OS Engine (Rust + Python)
        └── workspace/runs/

## Installation
```bash
pip install -r requirements.txt
streamlit run app_phaseos.py

## Installation
```bash
pip install -r requirements.txt
streamlit run app_phaseos.py

## Execution Modes
- **Demo Mode** – runs synthetic datasets (no Rust binary required)
- **Rust Mode** – connects to `phase-os` CLI if present in PATH or defined in `PHASE_OS_BIN`

## Folder Structure
phaseos-interface/
├── app_phaseos.py
├── python/
│   └── phase_plots_plos_complete.py
├── requirements.txt
└── workspace/
    └── runs/

## Interface Development Protocol v1.0
1. Build and test UI in Windows 11 (Codex + GitHub sub-account).
2. Export via USB.
3. Test with Phase-OS Engine on Ubuntu (air-gapped).
4. Return to Codex only if UI changes are needed.

## License
MIT License © 2025 Hee-Jong Yang

## Acknowledgment
Developed as part of the **Phase-OS** research project (RH–VERTEX–LOG Framework).
