# Module 12: Black-Box Optimisation

This work explores eight unknown functions using initial input/output observations, visualisations and Gaussian Process Bayesian optimisation with Expected Improvement.

## Files
- `module12_bayesian_optimisation.ipynb`: reproducible analysis and plotting
- `module12_query_points.csv`: suggested input points and best observations
- `Initial_data_points_starter(1).zip`: initial course data (place locally alongside notebook if sharing is permitted)

## Run
Install `numpy pandas matplotlib scipy scikit-learn jupyter nbformat`, then run the notebook. The notebook creates a `graphs/` folder.

## Method and caveats
All eight objectives are maximised. Outputs are standardised per function, then a Matérn Gaussian Process is fitted. Expected Improvement selects one new point from a Sobol candidate set. The domain `[0,1]^d` is assumed and must be confirmed. Predictions are not measured outputs, and no global-optimum guarantee is made.

## Weekly reflection
Document the acquisition strategy, the balance between exploration and exploitation, what the returned function value taught you, and the next round’s planned adjustments.
