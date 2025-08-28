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
Decision_Tree_with_Val.ipynb # decision tree modeling
gradient_boosting_model.ipynb # gradient boosting predictions
LinearRegression_with_val.ipynb # linear regression
Random_forest_with_predictions.ipynb # random forest predictions
SVM_val.ipynb # support vector machine model
ML_project_code.ipynb # main workflow notebook
data/
Solar_Weather_Final_Dataset.xlsx # raw dataset
solar_generation_selected_features.csv
visuals/
Solar_predictions_Dashboard.twbx # tableau workbook
recommendations.csv # model-based recommendations
docs/
Machine_Learning_Project_Report.pdf # full project report

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

