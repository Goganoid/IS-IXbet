# IS-IXbet
Student data science champ

## Setting up environment
```
conda env create -f environment.yml
```
## Project structure
- EDA.ipynb — EDA and training model process
- model.ipynb — data pipeline, evaluation of serialized model
- models/ — serialized models
- data/ — datasets
  - data/data.zip — original dataset
  - data/test.csv — subset for testing purposes in model.ipynb
- pandas-profiling-report.html — auto generated EDA
