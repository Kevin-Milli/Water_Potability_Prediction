# Water Potability Prediction

This project focuses on predicting water potability based on various chemical and physical variables. The goal is to develop predictive models that can determine whether the water is safe to drink or not.

## Description of Variables

The variables considered in this problem include:

- **pH**: Represents the pH value in water, measuring acidity or alkalinity on a scale from 0 to 14.
- **Hardness**: Indicates water hardness, measured in units of dissolved calcium and magnesium concentration.
- **Solids**: Represents the concentration of total dissolved solids in water, including inorganic and organic solids.
- **Chloramines**: Indicates the concentration of chloramines in water, used as a disinfectant.
- **Sulfate**: Represents the concentration of sulfates in water, influencing both taste and health.
- **Conductivity**: Measures water's ability to conduct electricity, influenced by the presence of ions.
- **Organic_carbon**: Indicates the concentration of organic carbon in water.
- **Trihalomethanes**: Represents the concentration of trihalomethanes in water, with health implications.
- **Turbidity**: Indicates water turbidity, i.e., its clarity or cloudiness.
- **Potability**: A binary variable (0 or 1) indicating whether the water is potable (1) or not potable (0) based on water quality criteria.

## Imports and Models Used

In the analysis process, common Python libraries were used for data processing and model creation, including Pandas, NumPy, Matplotlib, Seaborn, and various machine learning model classes such as AdaBoost, GradientBoosting, RandomForest, XGBoost, GaussianNB, KNeighbors, LogisticRegression, GaussianProcess, and SVC.

## Data Imbalance

It's important to note that the dataset exhibits class imbalance, with 61% of samples labeled as "Not Potable" and 39% as "Potable." This may impact the performance of predictive models and may require imbalance handling techniques.

## Results and Conclusions

Unfortunately, despite the analysis process and the use of various models, the final results were not satisfactory in accurately predicting water potability. This could be due to the complexity of the data or the need for additional data and model optimizations.

In the future, exploring more complex models or considering the acquisition of additional data may be beneficial in improving water potability prediction.

Feel free to explore the code and results of this project for further details.
