# CS598_FinalProject

To run the icu_los_prediction_tpc_model code, first set the data path in the notebook. Open the notebook at Code/icu_los_prediction_tpc_model.ipynb. Then, in the second code cell, locate the BASE_PATH variable. Replace the placeholder (...) with the correct path to your local data directory before running the notebook.<br>
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

To run tpc_los_model.ipynb, upload it to Google Colab along with the TPC-LoS-prediction folder (this might take a while). Then update the data path in the first code cell to match the location where TPC-LoS-prediction is mounted in your Google Drive. Recall that both of these codes don't provide results that correlate to the papers, but they follw the same idea.
