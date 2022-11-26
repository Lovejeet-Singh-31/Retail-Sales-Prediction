# Retail-Sales-Prediction
![640px-Rossmann_Logo svg](https://user-images.githubusercontent.com/104754645/174442537-0a299233-58b6-4ebf-9208-a62f5a7d82c5.png)
# 📖PROBLEM STATEMENT
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. My work includes various plots and graphs , visualizations , feature engineering , ensemble techniques , different ML algorithms with their respective parameter tuning , analysis and trends . Predictions are of 6 weeks of daily sales for 1,115 stores located across Germany.
# 📖ALGORITHMS USED:
### I. Linear Regression
### II. Linear Regression With Regularization
### III. Decision Tree
### IV. Ensemble Of Decision Trees
### V. K-NN

# 📖Solution Strategy
My strategy to solve this challenge was:

Step 01: Data Description: Use statistics metrics to identify data distribuctions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

Step 08: Deploy Modelo to Production: Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.
# 📖CONCLUSION
During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Sales' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable using corr() Function and for multicollinearity we use VIF Function defined by us. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented 8 machine learning algorithms Linear Regression,lasso,ridge,elasticnet,decission tree, Random Forest and XGBoost and Gredient Boosting. We did hyperparameter tuning to improve our model performance.

* The sales in the month of December is the highest sales among others.
* The Sales is highest on Monday and start declining from Tuesday to Saturday and on Sunday Sales almost near to Zero.
* Those Stores who takes participate in Promotion got their Sales increased.
* Type of Store plays an important role in opening pattern of stores. All Type ‘b’ stores never closed except for refurbishment or other reason.
* We can observe that most of the stores remain closed during State holidays. But it is interesting to note that the number of stores opened during School Holidays were more than that were opened during State Holidays.
* The R Squared score of all Liner Regression Algorithm with or without Regularization are quit good which is 0.76.
* the R Squared score of the Decision Tree Regressor model we got 0.83 on test set which is also good.
* The Random Forest regressor model perform very well amoung the others.
* The Gradient Boosting Regressor model perform well and give 0.88 R Squared on test set . After Applying GridSearchCV which is a optimal algorithm search tool improve our R Squared score from 0.88 to 0.94 which almost nearly the random forest regression model.
* There is no such over fitting seen.
* We can say that random forest regressor model is our optimal model and can be deploy.
# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
Mahima Phalkey | Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/lovejeet-singh31/) [![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/Lovejeet-Singh-31) [![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@lovebanna31) [![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)](https://drive.google.com/file/d/1JtAYLpo14I_-OEYQ7ylEeST66joC13Cz/view?usp=sharing)

