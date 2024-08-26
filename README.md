# MNIST_digit_recognition
MNIST is a subset of a larger set available from NIST (it's copied from http://yann.lecun.com/exdb/mnist/).
Here the objective is to make a classifier to classify the handwritten digits 0-9 and compute the accuracy of the classifier.
## Methodology:
I have first split the MNIST dataset into a roughly 70:30 training:test ratio using the train_test_split function from the scikit-learn library.
Then I have used the k-neighbours classification algorithm from the neighbours module, setting the numbers of nearest neighbours=5 to obtain more accuracy.
Now, I proceeded to the verification stage. 
Using the confusion_matrix function from the metrics module, I created a confsion matrix to form a an easily comprehensible performance report of the classifier.
Finally, I have used the seaborn library to create an intuitive visual representation of the confusion matrix.
In addition, I created  a classification report using the metrics module form the scikit-learn library to display various perfromance mtrics of the classifier like f1 score, precision, recall and support.


