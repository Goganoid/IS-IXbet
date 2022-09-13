# IS-IXbet
Student data science champ

## Важливе зауваження
Через помилку у коді замість метрики RMSE була використана MSE.
Тому справжній фінальний результат на тестових даних у model.ipynb такий: 
RMSE: 0.9684676610101581
MAPE: 6610524349892.934
MAE: 0.08032824488733463

## Setting up environment
```
conda env create -f environment.yml
```
## Launching
```
conda activate iasa
jupyter-lab
```
## Project structure
- EDA.ipynb — EDA and training model process
- model.ipynb — data pipeline, evaluation of serialized model
- models/ — serialized models
- data/ — datasets
  - data/data.zip — original dataset
  - data/test.csv — subset for testing purposes in model.ipynb
- pandas-profiling-report.html — auto generated EDA
