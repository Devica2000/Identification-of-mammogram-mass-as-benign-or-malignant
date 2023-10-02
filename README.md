# Identification of mammogram mass as benign or malignant
The aim of this project is to identify mammogram mass as benign or malignant. Several machine learning algorithms and neural networks will be used. At the end, I will do a comparison between all the approaches to see which one gives the best results. 

The first algorithms used is Decision Trees (with and without K-Fold validation) and Random Forest. 

Accuracy of decision trees without K-Fold validation: 75.25%
Accuracy of decision trees with K-Fold validation: 76.75%
Accuracy of random forest with K-Fold validation: 77.22%

The second algorithm used is SVM. Used the SVM algorithm for different kernels.
Accuracy with 'rbf' kernel = 80.12%
Accuracy with 'linear' kernel = 79.64%
Accuracy with 'sigmoid' kernel = 73.51%
Accuracy with 'poly' kernel = 79.27%

The third algorithm used is KNN. At K=10, the accuracy was 78.54%. 
Checked the accuarcy at different values of K from 1 to 49. The maximum accuracy was 79.40% at K=7.

The fourth algorithm used is Naive Bayes. Multinomial Naive Bayes has been used. It gives an accuracy of 78.44%.

The next algorithm used is logistic regression. It gives an accuracy of 80.7% at cv=10.

Lastly, neural networks have been implemented. It has an input layer with 6 input neurons. ReLu has been used as the optimizer here. The output layer has a single neuron since this is a binary classification problem. The optimer used is Sigmoid. The binary crossentropy loss has been found and Adam has been used as an optimizer. 
