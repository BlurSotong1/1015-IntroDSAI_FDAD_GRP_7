# Predicting Heart Disease Presence

## youtube video link for presentation:
https://youtu.be/eWcVlB4lWes

## dataset link:
https://www.kaggle.com/code/desalegngeb/heart-disease-predictions/notebook

## Overview
Heart diseases are a significant cause of mortality worldwide, with Singapore experiencing a high prevalence. This project aims to develop a predictive model to identify individuals at risk of heart disease based on various physical characteristics and medical attributes. By leveraging machine learning techniques and thorough data analysis, we seek to assist healthcare professionals in early detection, treatment, and prevention of heart diseases, ultimately reducing the number of deaths and improving the quality of life for affected individuals and their families in Singapore.

We used python to build a predictive model that included models such as Random Forest and Support Vector Machine.

## Dataset
The dataset used in this project contains information on various physical characteristics and medical attributes of individuals, sourced from [heart.csv](heart.csv). It includes features such as age, gender, chest pain type, resting blood pressure, serum cholesterol levels, fasting blood sugar, electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, the slope of the peak exercise ST segment, the number of major vessels, thalassemia, and the presence of heart disease.

## Project Structure
- **Data Cleaning and Preparation**: Renaming columns for clarity, dropping rows with NaN values and values out of range, and ensuring fairness in the distribution of disease presence labels.
- **Exploratory Data Analysis (EDA)**: Visualizing relationships between continuous variables and disease presence, noting surprising insights, examining boxplots, visualizing the distribution of disease presence across categorical variables, and using a correlation heatmap to understand the relationship between variables and disease presence.
- **Statistical Analysis**: Conducting t-tests and ANOVA to determine significant differences between groups with and without heart disease, and identifying variables for potential removal from the dataset based on p-values.
- **Insights and Recommendations**: Identifying significant factors associated with heart disease presence, making recommendations for feature selection, and providing insights for predictive modeling.
- **Data Visualization and Presentation**: Utilizing various plots and visualizations to convey insights, trends, and correlations within the data.

## Results
- Significant factors associated with heart disease presence include age, resting blood pressure, serum cholesterol levels, maximum heart rate achieved, ST depression induced by exercise, chest pain type, resting ECG results, the slope of the peak exercise ST segment, the number of major vessels, gender, and exercise-induced angina.
- Features such as serum cholesterol and fasting blood sugar, with p-values greater than 0.05, are recommended for removal from the dataset.
- Exploratory data analysis revealed surprising insights, such as the presence of a dual peak in disease presence at younger ages, and provided valuable information on the distribution and correlations of various factors with heart disease presence.

## Evaluation and Future Directions
- The predictive model developed in this project achieved an accuracy of 85.00% on the test dataset.
- Further refinements to the model could include feature engineering, hyperparameter tuning, and exploring advanced machine learning algorithms such as ensemble methods or neural networks.
- Future research could focus on incorporating additional data sources or expanding the scope of analysis to include other risk factors or comorbidities associated with heart diseases.

## Contributors
- Lee Choonggi (choonggi001@e.ntu.edu.sg)

## References

https://www.kaggle.com/code/desalegngeb/heart-disease-predictions/notebook
https://www.myheart.org.sg/health/heart-disease-statistics/#:~:text=In%20Singapore%2C%2023%20people%20die,to%20heart%20diseases%20or%20stroke.
https://www.analyticsvidhya.com/blog/2021/10/support-vector-machinessvm-a-complete-guide-for-beginners/
https://www.ibm.com/topics/random-forest
https://www.investopedia.com/terms/t/t-test.asp
https://www.investopedia.com/terms/a/anova.asp
https://www.ibm.com/docs/en/spss-modeler/saas?topic=models-how-svm-works
