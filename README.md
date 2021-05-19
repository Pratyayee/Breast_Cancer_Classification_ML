# Breast_Cancer_Classification_ML

# Data Set:
Import from SkLearn.datasets

# Explanation:
I have converted the dataset into a dataframe first to do the classification. Then I have splitted the dataset column wise into two parts, one is the predicted part and other is the target part. The dataset is also splitted row wise into two parts, train set and testing set with test size 0.3. I have scaled all the attributes of the data, because they are too much scattered. Then I have plotted the scaled dataset.

# Model Used: 
•	KNN – K Nearest Neighbourhood (N – neighbours = 7)
•	SVC – Support Vector Classifier (Linear Kernel)
•	SVC - Support Vector Classifier (RBF- Radial Basis Function)
•	MLP (Multi-Layer Perceptron)

# Result:
I)
•	KNN – K Nearest Neighbourhood (N – neighbours = 7) -
1.	Training Accuracy: 0.969
2.	Testing Accuracy: 0.959
3.	
•	SVC – Support Vector Classifier (Linear Kernel) -
1.	Training Accuracy: 0.990
2.	Testing Accuracy: 0.976
3.	
•	SVC – Support Vector Classifier (RBF- Radial Basis Function) -
1.	Training Accuracy: 0.987
2.	Testing Accuracy: 0.970
3.	
•	MLP (Multi-Layer Perceptron) -
1.	Training Accuracy: 0.990
2.	Testing Accuracy: 0.988
3.	
So, the Testing Accuracy of MLP is maximum. Therefore, MLP Classification is appropriate for the data according to the Testing Accuracy.

II) I have done 5-Fold Cross Validation on the whole data and computed the mean accuracies for all the models. We get that MLP has the highest accuracy. Therefore, MLP Classification is best for the data according to Cross Validation Score.
