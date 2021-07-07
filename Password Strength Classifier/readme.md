## Password Strength Classifier
> * This Project is worked on the password dataset.
> * In this Project data is loaded into dataframe and cleaned and anlayses the data. 
> * The Dataset is attached in the repository itself.
> * Analyses the different passwords and its strength and visualises them into graphs.
> * This is achieved by using using Logistic Algorithm.
> * Methods Worked On :
>    - TF-IDF

|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.59      | 0.30   | 0.39     | 18119   |
| 1            | 0.84      | 0.94   | 0.89     | 99248   |
| 2            | 0.82      | 0.69   | 0.75     | 16561   |
|              |           |        |          |         |
| Accuracy     |           |        | 0.82     | 133928  |
| Macro Avg    | 0.75      | 0.64   | 0.68     | 133928  |
| Weighted Avg | 0.80      | 0.82   | 0.80     | 133928  |

##### Label 0 : Weak password
##### Label 1 : Normal password
##### Label 2 : Strong password
