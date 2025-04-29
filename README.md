# CS598_FinalProject

To run the code, first set the Data Path in the Notebook. This is done by opening the notebook at "Created Code"/icu_los_prediction_tpc_model.ipynb. Then in the second code cell, locate the BASE_PATH variable. Replace the placeholder (...) with the correct path to your local data directory before running the notebook.
For example:
BASE_PATH = '/your/path/to/TPC-LoS-prediction/data/mimic_subset'

The required data files is organized like:
TPC-LoS-prediction/
├── data/
│   ├── mimic_subset/
│   │   ├── admissions.csv.gz
│   │   ├── icustays.csv.gz
│   │   ├── patients.csv.gz
|   |   ├── diagnoses_icd.csv.gz

The other aspects of the code in this folder are from the paper's GitHub repository: https://github.com/EmmaRocheteau/TPC-LoS-prediction
The other codes included in the "Create Code" folder, were for my testing purposes, and were attempts that didn't create any usable results.
