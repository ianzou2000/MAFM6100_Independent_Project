## MAFM6100_Independent Project

Our codes contain 2 models: daily model and high-frequency model.

### Daily Model

- **addDailyFactor.ipynb**
  - use Qlib to add 158 factors
- **runGRU_v6.ipynb**
  - model construction, training, prediction and backtesting

### High-Frequency Model

#### Model for Tick by Tick Data

- HF_lasso.ipynb
- HF_LGBM.ipynb

#### Model for Data sampled every 1 second

- HF_ridge_resample.ipynb
- HF_lgbm_resample.ipynb

#### Backtesting

- backtest.ipynb