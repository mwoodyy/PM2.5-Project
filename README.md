# PM2.5-Project
Dataset used: https://www.kaggle.com/datasets/djhavera/beijing-pm25-data-data-set

PM2.5 refers to fine particulate matter pollution with a diameter at most 2.5 micrometers

# Goals
Look at and analyze real world environmental data

Apply machine learning and evaluation metrics

Clearly visualize and understand results

# Process
Cleaned dataset by removing missing values in relevant columns

Plotted raw data of PM2.5 vs dew point to explore the relationship

Built a simple Linear Regression model to predict PM2.5 based on dew point

Evaluated model performance using R² score and root mean squared error (RMSE)

Visualized regression line with actual test values

# What I learned
PM2.5 and dew point have moderate positive correlation

Based on the model, more moisture -> more pollution (although other factors are surely involved)

Linear regression captured trend but did not explain variance (low R² score) which implies that a more complex model could offer more insights
