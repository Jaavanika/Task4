# Task4
1. Data Cleaning and Preparation
   
First, we cleaned the dataset by removing irrelevant columns and converting the diagnosis labels (M and B) into numerical values (1 for malignant and 0 for benign). This makes it easier for the machine learning model to understand and process the data.

2. Splitting and Scaling the Data
   
We split the dataset into training and testing sets so the model can learn patterns from one portion and be evaluated on unseen data. We also standardized the features so that each one has a similar scale, which helps the logistic regression model perform better.

3. Model Training and Prediction
   
We used logistic regression, which is great for binary classification problems like this. The model was trained on the scaled training data and then used to predict probabilities of cancer being malignant or benign on the test data.

4. Evaluating Performance
   
We assessed the model using metrics like precision, recall, and ROC-AUC score, and also plotted an ROC curve to visualize how well the model distinguishes between the two classes. These metrics help us understand how accurate and reliable our predictions are.

5. Exploring Different Thresholds & Understanding Sigmoid
   
By adjusting the classification threshold from 0.5 to 0.3, we saw how the model's precision and recall changed—showing the trade-off between catching more positives and reducing false alarms. We also explained the sigmoid function, which logistic regression uses to turn raw numbers into probabilities between 0 and 1.
