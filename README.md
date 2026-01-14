# DBAL (MNIST) — reproduction + last-layer regression extensions

This repo contains:
- a reproduction of the MNIST classification experiments from **Gal et al. (2017)** (Deep Bayesian Active Learning),
- additional **last-layer regression** experiments using ridge / BLR / MFVI (iid + correlated outputs) with predictive-variance-based acquisition and diversity-aware batch rules.

### Notebooks (main entry points)
- **`experiments_final.ipynb`**  
  Main notebook for the **classification reproduction** (Exp. 5.1 + Exp. 5.2), including the active-learning loop and plots.

- **`extension_new.ipynb`**  
  Main notebook for **regression / last-layer extensions** (ridge, BLR, MFVI; iid vs correlated outputs; batch-selection rules; metrics like RMSE/NLL/accuracy in the regression view).

### Result folders (per model)
- **`blr_iid/`**, **`blr_corr/`**, **`mfvi_iid/`**, **`mfvi_corr/`**  
  Saved outputs/plots for the corresponding model variants.  


### Other
- **`digits/`**
  Images acquired at round 0, 10, 50, 99.
