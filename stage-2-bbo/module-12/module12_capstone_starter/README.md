# Black-box optimisation capstone — Stage 2 (Module 12)

This folder contains initial data and exploratory analysis for the eight unknown functions in the Bayesian optimisation challenge. This is separate from Stage 1.

## Run the notebook

Install Python packages: `pip install numpy matplotlib scikit-learn jupyter`

Open a terminal in `notebooks/` and run `jupyter notebook module12_analysis.ipynb`. Run cells from top to bottom.

## Contents
- `data/initial_data/`: course-provided inputs and outputs for all eight functions
- `notebooks/module12_analysis.ipynb`: reproducible charts and illustrative GP prediction slices
- `images/`: graphs generated from the initial observations
- `results/initial_data_summary.csv`: initial observation counts and best values
- `results/module12_query_points.csv`: previously proposed candidate points, **not verified as optimal or submitted**
- `docs/`: course-provided datasheet and model-card templates (to be completed later)

## Method and limitations
Initial graphs show actual observations. GP plots show predictions along a slice, not the true objective. The true functions are hidden; only new portal queries can reveal new outputs. A query candidate must be checked against the data and actual submission before marking it submitted.

## Next steps
1. Review candidate queries, submit one per function through the portal.
2. Record the portal response and later returned output.
3. Update the dataset and model next module.
4. Complete the course discussion reflection (under 700 words).
