## Stock Sentiment Analysis
> * This Project is worked on the stock_data dataset.
> * The Analysis is done using the news headlines related to stocks from the dataset.
> * In this Project data is loaded into dataframe and cleaned and anlayses the data. 
> * Implemented the Bag of Words Model for the extracted headlines from the dataset.
> * Analyses the different passwords and its strength and visualises them into graphs.
> * This is achieved by using using RandomForest Classifier and Multinomial Naive Bayes Algorithm.
> * Methods Worked On :
>    - Bag of Words Method
> * Classification Report : RandomForest CLassifier
<center> 
  
|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.96      | 0.75   | 0.84     | 186     |
| 1            | 0.80      | 0.97   | 0.88     | 192     |
|              |           |        |          |         |
| Accuracy     |           |        | 0.86     | 378     |
| Macro Avg    | 0.88      | 0.86   | 0.86     | 378     |
| Weighted Avg | 0.88      | 0.86   | 0.86     | 378     | 
  
</center>

> * Classification Report : Multinomial NB

<center> 
  
|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.94      | 0.74   | 0.83     | 186     |
| 1            | 0.79      | 0.95   | 0.86     | 192     |
|              |           |        |          |         |
| Accuracy     |           |        | 0.85     | 378     |
| Macro Avg    | 0.86      | 0.84   | 0.84     | 378     |
| Weighted Avg | 0.86      | 0.85   | 0.84     | 378     |
  
</center>
