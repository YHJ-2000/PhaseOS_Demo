# Phase-OS Mini (Phases 1 – 4) — Offline Reproducibility Demo

This folder provides the executable materials accompanying  
**Yang H.-J. (2025). “RH–VERTEX–LOG Framework: Phases 1 – 4”** (submitted to *PLOS ONE*).

---

## 📦 Contents
| File | Description |
|------|--------------|
| `phaseos_mini.html` | Self-contained HTML demo implementing Phases 1–4. Runs fully offline. |
| `example_tau_sweep.csv` | Example τ-sweep output demonstrating the Phase 3 transition. |
| `cluster_preview.png` | Example Phase 4 vertex-cluster visualization (exported from the demo). |

---

## 🧮 How to Run (Offline)
1. **Download** `phaseos_mini.html` from this folder.  
2. **Open** the file in a modern browser (Chrome, Edge, Firefox, or Safari).  
3. **Adjust** parameters:
   - *Prime max* → upper limit for prime generation  
   - *β* → log-socket cutoff (Phase 2)  
   - *τ range* → start / end / step for the τ-sweep (Phase 3)  
   - *Cluster nodes* → number of vertices for Phase 4 preview  
4. Click **Run Phase 1–3** to compute the τ-sweep.  
5. Use the **Export τ-sweep CSV** or **Save Plot PNG** buttons to export results.  
6. For Phase 4, click **Draw Cluster** → **Save Cluster PNG**.  

💡 No installation, internet connection, or external library required.  
Works on both **desktop and mobile** browsers.

---

## 🧭 Phase Coverage
| Phase | Function | Observable |
|:------|:----------|:------------|
| 1 | Prime Gap Ratio ⟨r⟩ | Statistical order parameter for prime gaps |
| 2 | Log Socket Transform (β) | Low-frequency weighting of prime log spectra |
| 3 | τ-Sweep Simulation | Critical transition at τ* ≈ 0.145 (Poisson → GOE) |
| 4 | Vertex Cluster Preview | Emergent spectral coherence visualization |

---

## 🧪 Purpose
The Phase-OS Mini demo offers an openly reproducible environment for verifying  
the numerical and visual results discussed in the manuscript.  
It represents the computational backbone of the *RH-VERTEX-LOG* framework  
before its theoretical extensions (Phases 5–7).  

---

## 🔗 References & Links
- **Full theoretical framework (Phases 1–7):** [Zenodo DOI: 10.5281/zenodo.17467556](https://doi.org/10.5281/zenodo.17467556)  
- **Project repository:** [https://github.com/YHJ-2000/PhaseOS_Demo]  
- **License:** MIT License © 2025 Hee-Jong Yang  

---

> *For peer-reviewers and readers:*  
> This folder contains everything needed to reproduce the core computational figures  
> (τ-sweep and vertex cluster).  
> Results can be regenerated in under 60 seconds on a standard laptop or mobile device.
