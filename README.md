# depth-specific-water-temperature-framework
Code for EMS manuscript: depth-specific water temperature prediction framework

## Code structure
- `lstm_lime_pipeline`:  LIME-based feature contribution analysis.
- `automl_bayesian`:Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM model tuned via Bayesian optimization.
- `automl_hyperband`: Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM model tuned via Hyperband.
- `automl_nas`: Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM configuration explored via neural architecture search (NAS).
- `automl_random_search`: Depth-wise temperature prediction (separate models per depth) temperature prediction experiments using an  LSTM model tuned via random search.
