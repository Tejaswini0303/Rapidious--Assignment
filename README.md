# Rapidious--Assignment
In this project, I analyzed a dataset to predict whether a recipe is a dessert based on its nutritional values. I started by cleaning the data, removing rows with very high values and missing information. Then I split the dataset into training and testing parts.

I applied several machine learning models, including:

Logistic Regression: Achieved an accuracy of about 89.9%.
Gaussian Naive Bayes: Accuracy of 88.6%.
K Nearest Neighbors (KNN): Accuracy of 78.4%.
Support Vector Machines (SVM): Tried different kernels:
Linear: 91.1% accuracy.
RBF, Polynomial, and Sigmoid: Each got 81.6% accuracy.
Decision Tree: Gave an accuracy of 89.9%.
Random Forest: Performed the best with 93% accuracy.
AdaBoost: Accuracy of 84.8%.
Lastly, I used KMeans clustering to group the data based on calorie and fat values and visualized the clusters in a scatter plot.

Overall, Random Forest provided the highest accuracy, making it the most effective model for this task.
