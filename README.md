# CS598_FinalProject

To run the icu_los_prediction_tpc_model.ipynb code, open the notebook at Code/icu_los_prediction_tpc_model.ipynb. Then, in the second code cell, locate the BASE_PATH variable. Then replace the placeholder (...) with the correct path to your local data directory before running the notebook.<br>
For example:<br>
BASE_PATH = '/your/path/to/TPC-LoS-prediction/data/mimic_subset'

The required data files is organized like this:<br>
TPC-LoS-prediction/<br>
├── data/<br>
│   ├── mimic_subset/<br>
│   │   ├── admissions.csv.gz<br>
│   │   ├── icustays.csv.gz<br>
│   │   ├── patients.csv.gz<br>
│   │   ├── diagnoses_icd.csv.gz<br>

The other components of the code in this folder are from the paper's GitHub repository:<br>
https://github.com/EmmaRocheteau/TPC-LoS-prediction<br>

To run the tpc_los_model.ipynb code, similar to the other Jupyter notebook, open the notebook at Code/tpc_los_model.ipynb. Then, in the second code cell, locate the raw_path variable. Then replace the placeholder (...) with the correct path to your local data directory before running the notebook.
