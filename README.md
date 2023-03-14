# nidhinsanju.1
Intrusion detection using SVM,KNN,RF and then creating a ensemble model by using voting classifier and showing the results in a graph. Confusion matrix for the SVM,KNN,RF are show which shows the value . IT is done Using  the supervised Machine Learning algorithms
The given code is an implementation of different classification algorithms such as Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Random Forest (RF) on a dataset.
The dataset is loaded using Pandas and then split into training and testing sets using the train_test_split method from sklearn. The SVM, KNN, and RF models are trained using their respective classes from sklearn. Then, predictions are made on the testing set using each model and the accuracy, recall, and precision scores are calculated for each model using their respective methods from sklearn.metrics.
The confusion matrix is generated for each model using the confusion_matrix method from sklearn.metrics, and the results are plotted using Matplotlib.
Finally, an ensemble model is created using the VotingClassifier class from sklearn, and predictions are made on the testing set using this model. The accuracy, recall, and precision scores for the ensemble model are also calculated and printed along with the scores for the individual models.
The results of all models are stored in a Pandas dataframe named 'results'.
