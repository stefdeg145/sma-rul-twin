# SMA RUL Digital Twin

Physics-informed LSTM for predicting the remaining useful life (RUL)
of shape memory alloy (SMA) actuators undergoing functional fatigue.

## Status
In progress. Preprocessing pipeline complete; baseline model next.

## Structure
- `notebooks/01_synthetic_data.ipynb` — Coffin-Manson synthetic data generator
- `notebooks/02_preprocessing.ipynb` — feature engineering, windowing, cycle-stratified split
- `src/` — clean modules (coming as code stabilizes)
- `data/` — regenerable, not version-controlled

## Reproduce
Run `01_synthetic_data.ipynb` to generate the dataset, then
`02_preprocessing.ipynb` to build model-ready tensors.
