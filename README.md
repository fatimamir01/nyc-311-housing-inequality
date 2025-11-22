# nyc-311-housing-inequality
NYC 311 — Housing Inequality Analysis (Freshman Project)
# NYC 311 — Housing Inequality Analysis (Freshman Project)

**Author:** Farima Mir
**Tools:** Python, pandas, matplotlib, seaborn (optional)  
**Date:** 2025

## Project summary
This beginner-level project analyzes NYC 311 service requests related to housing problems (heat/hot water, mold, pests, housing maintenance, illegal evictions) to explore patterns that may reflect housing inequality across boroughs. The goal is to practice data cleaning, exploratory analysis, and storytelling with real city data.

## Research questions
1. Which housing-related complaint types are most common in NYC overall and by borough?  
2. Do boroughs differ in complaint volumes for housing problems?  
3. How do housing complaints trend over time (monthly), and are there seasonal spikes?

## What’s included
- `notebooks/311_housing_inequality_analysis.ipynb` — full analysis notebook (data loading, cleaning, visualizations, findings)
- `requirements.txt` — Python packages needed
- `data/README.md` — instructions to download the 311 CSV from NYC Open Data
- `artifacts/figures/` — optional folder for saved plots

## How to run
1. Clone the repo.
2. Download the 311 dataset CSV (instructions in `data/README.md`) and save it as `data/311-service-requests.csv`.
3. Create a Python environment and install requirements:
   ```bash
   python -m venv venv
   source venv/bin/activate  # mac/linux
   pip install -r requirements.txt
