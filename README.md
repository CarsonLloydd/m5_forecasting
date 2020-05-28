# Forecasting Walmart sales
m5 Forecasting competition on kaggle

All data can be found here - https://www.kaggle.com/c/m5-forecasting-accuracy

## Repository format
* fst_lgbm.ipynb - fast lgbm model baseline with basic lag and rolling mean features
* mod_lgbm.ipynb - more in depth tuned lgbm model that incorporates the two major breakthroughs found in the kaggle competition.
Using poisson loss instead of MSE, and using step by step predictions instead of forecasting all 28 days at once.
* m5_eda - visual analysis of sales by stores, items, category, etc.
