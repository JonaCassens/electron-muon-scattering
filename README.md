# Statistical Analysis of Angular Asymmetries in e⁺e⁻ → μ⁺μ⁻ Scattering

Simulates electron–positron collisions near the Z resonance and measures a small forward–backward asymmetry (κ). Synthetic angular datasets are generated with inverse transform sampling and fitted with three methods matched to data size: unbinned likelihood (5k events), binned likelihood (50k events), and χ² (500k events). Plots and summaries show how κ precision improves with more events.

## Files
- `ElectronMuonScattering.ipynb` — main notebook with simulation, fits, and plots.
- `simple_drawing.png` — schematic of the scattering angle.

## Environment
```bash
python -m venv .venv
source .venv/bin/activate
pip install numpy scipy matplotlib iminuit jupyter
```

## Run
```bash
jupyter notebook ElectronMuonScattering.ipynb
```

## What you’ll see
- Generated angular distributions for κ = −0.07, 0, +0.07
- Fits for each scenario with κ estimates and uncertainties
- Comparison of methods and how precision scales with event count
