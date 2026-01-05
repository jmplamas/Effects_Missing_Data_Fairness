This repository contains the Individual Assingment for the [Artificial Intelligence and Society](https://sigarra.up.pt/fcup/en/UCURR_GERAL.FICHA_UC_VIEW?pv_ocorrencia_id=559505) course of the Master's in Artificial Intelligence at the University of Porto.
The project studies how missing data and different imputation methods can affect model performance and fairness.

## 📂 Project Structure
- `Data/`: Folder containing the dataset files.
  - `adult.csv`: Adult Census Income dataset.
  - `compas-scores-two-years.csv`: COMPAS Recidivism (2 years) dataset.
  - `german_credit_data.csv`: German Credit Data dataset.
- `main.ipynb`: Jupyter notebook containing the implementation of data preprocessing, model training, evaluation, and fairness assessment.
- `IAS_Individual_Assignment_Report.pdf`: PDF report detailing the methodology, experiments, results, and conclusions of the project.
- `<name>.csv files`: CSV files containing results from experiments.

## ⚙️ Requirements & How to Run
- Python 3.12.12 (project tested on this version, it could also work on other 3.x versions but not guaranteed)
- Dependencies listed in `requirements.txt`. Can be installed via pip:
  ```bash
  pip install -r requirements.txt
  ```
- Run the notebook `main.ipynb` in a Jupyter environment to reproduce the experiments.
- The experiments contain a detailed explanation of each step, from data preprocessing to model evaluation.
- It has a focused analysis of a specific seed (42), but at the end of the notebook, there is a section that runs all experiments for multiple seeds (50) to analyse stability and saves the results in CSV files.