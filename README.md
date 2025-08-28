```
# solar energy generation prediction

## overview
this project predicts **solar energy generation** using historical weather and solar data. multiple machine learning models were built and compared, including **linear regression, random forest, gradient boosting, decision trees, and svm**. results support accurate forecasting and energy planning, with visualizations created in tableau for better insights.

## key features
- cleaned and engineered historical solar and weather datasets  
- implemented linear, tree-based, and ensemble models for prediction  
- evaluated models using **mae, rmse, and r²** to compare performance  
- generated actionable recommendations for improving energy predictions  
- created an interactive **tableau dashboard** for visual exploration  

## repository structure
```

notebooks/
Decision\_Tree\_with\_Val.ipynb     # decision tree modeling
gradient\_boosting\_model.ipynb    # gradient boosting predictions
LinearRegression\_with\_val.ipynb  # linear regression
Random\_forest\_with\_predictions.ipynb  # random forest predictions
SVM\_val.ipynb                    # support vector machine model
ML\_project\_code.ipynb            # main workflow notebook
data/
Solar\_Weather\_Final\_Dataset.xlsx     # raw dataset
solar\_generation\_selected\_features.csv
visuals/
Solar\_predictions\_Dashboard.twbx     # tableau workbook
recommendations.csv                  # model-based recommendations
docs/
Machine\_Learning\_Project\_Report.pdf  # full project report

````

## how to run
1. **clone the repository**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
````

2. **install dependencies**

   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```

3. **run the notebooks**
   open any notebook in `notebooks/` using jupyter lab or jupyter notebook and execute cells sequentially.

4. **view the dashboard**
   open the Tableau workbook in `visuals/` for interactive charts and predictions.

## license

this project is licensed under the [MIT License](./LICENSE).

