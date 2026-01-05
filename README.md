# depth-specific-water-temperature-framework
Code for EMS manuscript: depth-specific water temperature prediction framework

## Code structure
- `lstm_lime_pipeline`:  LIME-based feature contribution analysis.
- `automl_bayesian`:Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM model tuned via Bayesian optimization.
- `automl_hyperband`: Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM model tuned via Hyperband.
- `automl_nas`: Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM configuration explored via neural architecture search (NAS).
- `automl_random_search`: Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM model tuned via random search.


## Data availability

Observed reservoir data used in this study were provided by K-water and are not publicly available due to data sharing restrictions.
Hydrodynamic simulation outputs generated using CE-QUAL-W2 were used as model inputs and are described in detail in the manuscript.
All data sources and preprocessing steps required to reproduce the modeling framework are documented in the paper.
