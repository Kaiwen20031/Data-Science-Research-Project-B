# Data-Science-Research-Project-B
The main analysis is stored in the `Code/` folder. The notebooks use relative paths, so the folder structure should not be changed.
## File structure

```text
Project root/
|-- Code/
|-- Data/
|   |-- raw data/
|   |-- processed_data/
|   `-- model_data/
|-- Figures/
|-- Results/
|   `-- Model_selection/
`-- Part A/
```
## Main analysis

Open the notebooks from the `Code/` folder and run all cells in the following order:

1. `01_surveydatacleaning.ipynb`
2. `02_policydatacleaning.ipynb`
3. `03_merge_and_encode.ipynb`
4. `04_prepare_model_datasets.ipynb`
5. `05_logistic_regression.ipynb`
6. `06_decision_tree.ipynb`
7. `07_random_forest.ipynb`
8. `08_xgboost.ipynb`
9. `09_final_model.ipynb`
10. `10_feature_importance.ipynb`
11. `11_supplement.ipynb`

The notebooks were developed in Jupyter Notebook using Python 3.12.7, scikit-learn 1.5.1 and XGBoost 3.0.0.

Input data are stored in `Data/raw data/`. Intermediate and final datasets are written to `Data/processed_data/` and `Data/model_data/`. Model results are written to `Results/`. Figures generated in the notebooks were saved manually in the `Figures/` folder.
## Replication analysis

The replication files are stored separately in the `Part A/` folder. Run the notebooks in the following order:

1. `clean.ipynb`
2. `datasplit.ipynb`
3. `LR.ipynb`
4. `Decision Tree.ipynb`
5. `XGBoost.ipynb`
6. `RF.ipynb`
7. `final_model.ipynb`
8. `important_feature.ipynb`

## Author
Kaiwen Du
