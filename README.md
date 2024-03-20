# Breast Cancer Data Models
The three main models I have chosen include Logistic Regression, Decision Tree, and SVM. All other techniques applicable to this problem include Random Forests, K-Nearest Neighbors (KNN), Neural Networks, and Gradient Boosting Machines (GBM). In this project I looked at the original, oversampled, and under sampled models for Logistic Regression, Decision Tree, and SVM: 

Model Analysis:


Original Models:

•	Logistic Regression: Shows a good balance between precision and recall across both classes, with an overall accuracy of 0.890625.

•	Decision Tree: Offers comparable performance to logistic regression, with slightly better recall for the positive class but lower precision.

•	SVM: The performance is lower than the other two models in accuracy and f1-score.
 

Oversampled Models:

•	Logistic Regression: The performance remains consistent with the original model, showing a slight improvement in precision for the positive class.

•	Decision Tree: Shows a slight decrease in overall accuracy and precision for the positive class compared to the original model.

•	SVM: Demonstrates an improvement in recall for the positive class but a decrease in precision for the negative class compared to the original SVM.
 

Under sampled Models:

•	Logistic Regression: Shows the best overall accuracy among all models at 0.90625, with improved recall for the negative class and precision for the positive class.

•	Decision Tree: While the accuracy is close to the original and oversampled models, there's a slight improvement in the recall for the positive class.

•	SVM: Shows a drop in performance across most metrics compared to the original and oversampled versions.

 
Best Model:

When comparing all models, the Under sampled Logistic Regression model stands out as the best, with the highest overall accuracy and a strong balance between precision and recall. It demonstrates an improvement, specifically in the recall for the negative class and precision for the positive class.
 
Conclusion:

The Under sampled Logistic Regression model is the best choice among the models tested. It provides a great performance, making it a suitable model for predicting breast cancer in this scenario. 
