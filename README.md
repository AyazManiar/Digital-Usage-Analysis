# Digital Usage Analysis


## What this repo contains

- Notebooks
	- `SIN_Ayaz_Ruchin.ipynb` — primary exploratory analysis and visualizations.
- Dataset
	- `Dataset/final_fg_events.csv` — final cleaned dataset used by the notebooks.
- Images
	- `Images/` — output figures and presentation images used in reports.
- Presentations
	- `SIN Project PPT.pdf` / `SIN Project PPT.pptx` — presentation slides.

## Purpose

This repository holds data and Jupyter notebooks used to analyze FG events. Notebooks are runnable end-to-end and produce the figures stored in `Images/`.

## Quick start

1. Create and activate a Python virtual environment (recommended):

	 - Windows (PowerShell):

		 ```powershell
		 python -m venv .venv
		 .\.venv\Scripts\Activate.ps1
		 ```

2. Install dependencies:

	 ```powershell
	 pip install -r requirements.txt
	 ```

3. Open the notebook you want to run in Jupyter or VS Code and run cells in order:

	 - Start Jupyter:

		 ```powershell
		 jupyter notebook
		 ```

	 - Or open the `.ipynb` files in VS Code (recommended if you use the Python extension).

4. Recommended order to run:
	 1. `SIN_Ayaz_Ruchin.ipynb` (exploration)
	 2. `combined_final_fg_events_analysis.ipynb` (merged/final analysis)

## Notes about data

- `Dataset/final_fg_events.csv` is the canonical CSV used by the notebooks. It is included in the repo.
- Notebooks assume the dataset path `Dataset/final_fg_events.csv` — update the path in the notebook if you move the file.

## Minimal requirements

See `requirements.txt` for the minimal packages to run the notebooks. Typical environment: Python 3.8+.

## Output

- Generated figures and exports are saved in `Images/`.
- Use the notebooks to reproduce figures used in the presentations.
