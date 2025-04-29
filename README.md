# CS598_FinalProject

To run the code, first set the Data Path in the Notebook. This is done by opening the notebook at "Created Code"/icu_los_prediction_tpc_model.ipynb. Then in the second code cell, locate the BASE_PATH variable. Replace the placeholder (...) with the correct path to your local data directory before running the notebook.<br>
For example:<br>
BASE_PATH = '/your/path/to/TPC-LoS-prediction/data/mimic_subset'

The required data files is organized like:<br>
TPC-LoS-prediction/<br>
├── data/<br>
│   ├── mimic_subset/<br>
│   │   ├── admissions.csv.gz<br>
│   │   ├── icustays.csv.gz<br>
│   │   ├── patients.csv.gz<br>
│   │   ├── diagnoses_icd.csv.gz<br>

The other aspects of the code in this folder are from the paper's GitHub repository: https://github.com/EmmaRocheteau/TPC-LoS-prediction<br>
The other codes included in the "Create Code" folder, were for my testing purposes, and were attempts that didn't create any usable results.
