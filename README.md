# CMF
Here you can find my work for the second stage in CMF course

Data for the project can be found here: https://www.kaggle.com/datasets/franciscofeng/augmented-china-stock-data-with-fundamentals

You can fine-tune the parameters of the model by changing block "Parameters which will be fine-tuned" in ipynb file. 
Here you can modify data intervals, window size and percentiles. Don't forget to change calculation of the Sharpe Ratio if your data is smaller than 1 year. Write annualize=False/or True in function: qs.stats.sharpe(df_daily_return, rf=0.05, annualize=False)
