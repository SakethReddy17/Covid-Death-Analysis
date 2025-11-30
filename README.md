OVERVIEW

A logistic regression model in COVID-19 death analysis primarily symbolizes a tool for quantifying risk factors and predicting the probability of mortality for individual patients or specific population subgroups.

SIGNIFICANCE

1) Risk Quantification
2) Probability Prediction
3) Clinical Decision Support
4) Controlling Confounding Factors

SETUP

Open the ipynb file and upload any covid dataset from kaggle into it. Make sure that the drive is mounted and packages are installed to run the code and display the results.

OPERATIONS

1) Display the first few rows of the DataFrame
   
| index | USMER | MEDICAL_UNIT | SEX | PATIENT_TYPE | DATE_DIED  | INTUBED | PNEUMONIA | AGE | PREGNANT | DIABETES | COPD | ASTHMA | INMSUPR | HYPERTENSION | OTHER_DISEASE | CARDIOVASCULAR | OBESITY | RENAL_CHRONIC | TOBACCO | CLASSIFICATION_FINAL |
| ----- | ----- | ------------ | --- | ------------ | ---------- | ------- | --------- | --- | -------- | -------- | ---- | ------ | ------- | ------------ | ------------- | -------------- | ------- | ------------- | ------- | -------------------- |
| 0     | 2     | 1            | 1   | 1            | 03/05/2020 | 97      | 1         | 65  | 2        | 2        | 2    | 2      | 2       | 1            | 2             | 2              | 2       | 2             | 2       | 3                    |
| 1     | 2     | 1            | 2   | 1            | 03/06/2020 | 97      | 1         | 72  | 97       | 2        | 2    | 2      | 2       | 1            | 2             | 2              | 1       | 1             | 2       | 5                    |
| 2     | 2     | 1            | 2   | 2            | 09/06/2020 | 1       | 2         | 55  | 97       | 1        | 2    | 2      | 2       | 2            | 2             | 2              | 2       | 2             | 2       | 3                    |
| 3     | 2     | 1            | 1   | 1            | 12/06/2020 | 97      | 2         | 53  | 2        | 2        | 2    | 2      | 2       | 2            | 2             | 2              | 2       | 2             | 2       | 7                    |
| 4     | 2     | 1            | 2   | 1            | 21/06/2020 | 97      | 2         | 68  | 97       | 1        | 2    | 2      | 2       | 1            | 2             | 2              | 2       | 2             | 2       | 3                    |

2) Generate seaborn heatmap

<img width="592" height="564" alt="image" src="https://github.com/user-attachments/assets/3ae6ddeb-5381-48f2-a3f9-143b102f5d3b" />

3) Confusion matrix plot

<img width="559" height="455" alt="image" src="https://github.com/user-attachments/assets/f727faaf-3631-4818-a19f-7d8791aa0275" />


ACCURACY: 0.88 after processing the data frames by dropping unnecessary rows and columns for training and testing purposes
   
