# Accelerated Stability Analysis - KTP Assessment

This repository contains a short data analysis notebook for the KTP Associate pre-interview exercise.

The analysis compares two prototype formulations, Lot A014 and Lot B025, using accelerated stability data. It focuses on:

- data structure and quality checks
- exploratory visual analysis
- degradation trends across exposure time, temperature, and humidity
- comparison of formulation stability
- simple interpretable modelling
- limitations and recommendations for future study design

## Repository structure

```
.
├── stability_analysis.ipynb
├── requirements.txt
├── README.md
├── data/
└── plots/
```

The supplied Excel dataset is **not included** in this repository. Place it in the `data/` folder as:

```
data/KTP_task_datasets.xlsx
```

## How to run

Create a virtual environment and install the requirements:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook stability_analysis.ipynb
```

## Notes

The modelling is intentionally simple and interpretable because the dataset is small. The goal is to support scientific reasoning and decision-making rather than produce a complex black-box prediction model.