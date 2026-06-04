# SI Symmetry Numbers

This repository contains the supporting-information notebooks, reference data,
and exported reports used for the symmetry-number manuscript experiments.

## Contents

- `data/`: reference datasets used by the notebooks.
- `notebooks/`: Jupyter notebooks and small notebook helpers.
- `reports/`: exported HTML reports generated from selected notebooks.
- `pyproject.toml`: Python dependency metadata for reproducing the notebook environment.

## Environment

The notebooks target Python 3.13+.

Install the environment with:

```bash
pip install -e .
```

The main runtime dependencies are `stereomolgraph`, `rdkit`, `pandas`, and
`ipykernel`.

## Data Provenance

`data/kinbot.csv` contains the KinBot benchmark data used for the manuscript's
topological symmetry-number comparison.

The benchmark originates from:

> Van de Vijver, R.; Zador, J. KinBot: Automated Stationary Point Search on
> Potential Energy Surfaces. *Computer Physics Communications* **2020**, *248*,
> 106947. https://doi.org/10.1016/j.cpc.2019.106947

The CSV in this repository is the local benchmark table used by the notebooks
for reproducing the manuscript comparisons.