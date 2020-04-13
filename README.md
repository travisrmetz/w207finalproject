## W207 Spring 2020, Wednesday 6:30pm section, Holloway
#### Kaggle: House Prices: Advanced Regression Techniques
#### Team:  Imran Manji, Madhukar Reddy, Travis Metz


Cloning this repo should bring down both the relevant notebooks and data files for work on the Ames Housing Price project on Kaggle.

We have two notebooks that do front to back analysis.  

#### `w207_final_project.ipynb`
This notebook loads previously optimized models from `best_models.pkl` so that the parameter search process at end of notebook is not required for each load -- it takes roughly 10 minutes.

Use `conda env create -f environment.yml` and then `conda activate base` for appropriate dependencies.

A secondary error analysis notebook related to this analysis is contained in `error_analysis.ipynb`


#### `W207.6_Spring2020_Ames_Home_Price_Prediction_revised.ipynb`
This notebook also loads previously optimized models from `best_models_file.pkl`.
The parameter search code is contained near bottom of notebook.
This notebook was primarily developed in colab.
