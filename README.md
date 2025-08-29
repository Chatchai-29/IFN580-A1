# IFN580 A1 — Team Setup (Short README)

> Goal: everyone runs the *same* environment and workflow. Keep this repo **private**.

## Repo structure
IFN580-A1/
├─ data/            # (ignored) put kick.csv here — DO NOT COMMIT
├─ notebooks/
│  ├─ A1_Task1_prep.ipynb
│  ├─ A1_Task2_DT.ipynb
│  ├─ A1_Task3_LogReg.ipynb
│  └─ A1_Task4_MLP.ipynb
├─ figures/         # generated plots (optional: can ignore)
├─ report/          # doc/pdf assets
├─ environment.yml  # shared conda env
├─ .gitignore
└─ README.md

## 1) Environment (once per machine)
- Install **Anaconda** (Python 3.12+).
- If `environment.yml` exists:
```bash
conda env create -f environment.yml
conda activate ifn580
